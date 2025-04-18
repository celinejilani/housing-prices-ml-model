## Project Overview
This project uses machine learning to predict real estate sale prices using public housing data from Seattle (2014–2015 and 2023). We apply a Random Forest Regression model to learn relationships between key variables affecting price, such as square footage, location, and condition.

The purpose is to provide stakeholders—such as buyers, sellers, and agents—with more informed decision-making tools by leveraging modern ML techniques over traditional methods.

## How to Use
1. Run `data_pipeline.ipynb` to clean and preprocess the dataset.
2. Open `housing_prices_ml.ipynb` to train and evaluate the Random Forest model.
3. Use `fastapi_app.py` or `streamlit_app.py` to interact with the model and make predictions.
4. Explore model versioning and tracking via MLflow (planned in next iteration).

## Challenges and Next Steps
While the Random Forest model gives decent predictions, performance metrics are not yet optimal. Our next step is to train a Neural Network for comparison and log results using MLFlow.

## Contributors
- @lapecs – Project lead, modeling
- @celinejilani – README documentation and team contribution
