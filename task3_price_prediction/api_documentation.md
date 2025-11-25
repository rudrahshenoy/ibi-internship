# Product Recommendation API Documentation

## Endpoints

### POST /predict
Input JSON:
{
  "product_id": 123,
  "user_id": 45
}

Response:
{
  "recommended_products": [...]
}
