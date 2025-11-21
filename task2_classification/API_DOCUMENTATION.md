# API Documentation - Ecommerce Product Categorization

Files:
- `model.pkl` - scikit-learn pipeline (TF-IDF + LogisticRegression + LabelEncoder)
- `model_placeholder.h5` - HDF5 file containing the pickled sklearn pipeline (for convenience)
- `environment.yml` - conda environment
- `predict_api.py` - example FastAPI app
- `notes.txt` - training notes and metrics

Dataset used: SYNTHETIC

Scikit-learn accuracy on test set: 1.0000

Classification report:
                precision    recall  f1-score   support

         Books       1.00      1.00      1.00        24
      Clothing       1.00      1.00      1.00        24
   Electronics       1.00      1.00      1.00        24
Home & Kitchen       1.00      1.00      1.00        24
        Sports       1.00      1.00      1.00        24

      accuracy                           1.00       120
     macro avg       1.00      1.00      1.00       120
  weighted avg       1.00      1.00      1.00       120