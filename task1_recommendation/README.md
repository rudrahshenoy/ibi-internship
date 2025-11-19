Ecommerce Product Recommendation System

A machine-learning powered product recommendation engine using collaborative filtering and ranking-based techniques. This repository includes Jupyter notebooks, visualizations, and a deployable API for generating user and item-level recommendations.

Features

-User-based collaborative filtering
-Item-based collaborative filtering
-Ranking-based product recommendations
-Cold-start solutions
-Fully documented API
-Clean modular workflow
-Visualizations included

Tech Stack

-Python 3.10
-Pandas, NumPy
-Scikit-Learn
-Matplotlib, Seaborn
-Jupyter Notebook

Project Structure
├── notebooks/
│   ├── User_based_collaborative_filtering.ipynb
│   ├── Model_based_collaborative_filtering.ipynb
│   ├── rank_based_product_recommendation.ipynb
│   └── ColdStartProblem.md
├── api/
│   └── app.py (optional)
├── README.md
├── requirements.txt
└── environment.yml

Setup Instructions
1. Clone the repository
git clone https://github.com/yourusername/ecommerce-recommendation-system.git
cd ecommerce-recommendation-system

2. Create environment

Option A — Using requirements.txt

pip install -r requirements.txt


Option B — Using Conda (recommended)

conda env create -f environment.yml
conda activate recommendation-env

3. Run Jupyter Notebooks
jupyter notebook

4. Run the API (FastAPI Example)
uvicorn api.app:app --reload


Open browser:

http://127.0.0.1:8000/docs

API Documentation

See full API reference in API Documentation

Visualizations

Includes:
-User–item heatmaps
-Rating distribution plots
-Similarity matrices
-Top-N recommendations analytics