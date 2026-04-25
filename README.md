# Farm Crop Yield Prediction

A linear regression model that predicts crop yield (tons) from rainfall (mm) using scikit-learn.

## Dataset

`farm_data.csv` — 13 samples with two columns:
- `Rainfall_mm`: rainfall in millimeters (400–1000)
- `Crop_Yield_tons`: crop yield in tons

## Files

| File | Description |
|------|-------------|
| `fam.ipynb` | Main notebook: data loading, model training, evaluation, and submission export |
| `linear_regression.py` | Standalone script stub for loading the dataset |
| `farm_data.csv` | Input dataset |
| `submission.csv` | Model predictions on the test set |

## Results

| Metric | Value |
|--------|-------|
| MSE | 0.000926 |
| R² | 0.9997 |

## Setup

```bash
python -m venv ds_pandas
source ds_pandas/bin/activate
pip install pandas scikit-learn jupyter
jupyter notebook fam.ipynb
```
