# California Housing Price Prediction (Regression)

A student project to predict **median house values** in California using the **California Housing Dataset** from `scikit-learn`.

## Models
- **Linear Regression**
- **Polynomial Regression (degree = 2)**

## Evaluation Metrics
- RMSE
- MAE
- R²

## Visuals
- Correlation heatmap
- Predicted vs. actual scatter plot

## Files
- `california_housing.ipynb` — data loading, preprocessing, training, evaluation, plots
- `plots/` — saved figures
- `requirements.txt` — dependencies
- `LICENSE`

## Run
```bash
git clone https://github.com/your-username/california-housing-regression.git
cd california-housing-regression
pip install -r requirements.txt
jupyter notebook california_housing.ipynb
Dataset
Features include longitude, latitude, housing age, rooms, bedrooms, population, households, and median income.
Target: median_house_value.
