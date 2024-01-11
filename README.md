# Vehicle Price Prediction

This project aims to predict vehicle prices based on vehicle features, brand, and model information. The prediction model has been trained using a machine learning model, specifically a gradient boosting algorithm.

## Files

- `brand_average_prices.json`: File containing average prices based on vehicle brands.
- `brand_id_dict.json`: File containing brand IDs and their corresponding labels.
- `model_average_prices.json`: File containing average prices based on vehicle models.
- `model_id_dict.json`: File containing model IDs and their corresponding labels.
- `fuel_average_prices.json`: File containing average prices based on fuel types.
- `fuel_id_dict.json`: File containing fuel IDs and their corresponding labels.
- `brand_model_id_dict.json`: File containing IDs for brand and model combinations.
- `model_fuel_id_dict.json`: File containing IDs for model and fuel combinations.
- `ai.pickle`: Pre-trained machine learning model.

## Requirements

Make sure you have the following before running the prediction script:

- Python
- Required Python packages (NumPy, pandas, scikit-learn, joblib)

Install the necessary packages using the following command:

```bash
pip install numpy pandas scikit-learn joblib
