# House Price Prediction

Internship Project — Week 1

## What this project does
Predicts house prices using property features like area, bedrooms, bathrooms, and amenities, and finds out which features affect price the most.

## Dataset
`Housing.csv` — 545 properties, 13 features (price, area, bedrooms, bathrooms, stories, mainroad, guestroom, basement, hotwaterheating, airconditioning, parking, prefarea, furnishingstatus).

## What's in this repo
- `analysis.ipynb` — full notebook (data cleaning, model training, charts, insights)
- `Housing.csv` — dataset used
- `summary.docx` — 1-page write-up of findings
- `charts/` — the 3 saved chart images

## Steps done
1. Loaded and explored the data
2. Cleaned it (checked nulls/duplicates, encoded categorical columns)
3. Trained a Linear Regression model and a Random Forest model, compared them
4. Made 3 charts: price distribution, correlation heatmap, actual vs predicted price
5. Wrote up findings and a recommendation

## Results
| Model | MAE (₹) | RMSE (₹) | R² Score |
|---|---|---|---|
| Linear Regression | 9,70,043 | 13,24,507 | 0.65 |
| Random Forest | 10,14,947 | 13,99,769 | 0.61 |

Area and bathroom count turned out to be the biggest drivers of price.

## How to run
1. Open `analysis.ipynb` in Jupyter Notebook or Google Colab
2. Make sure `Housing.csv` is in the same folder
3. Run all cells
