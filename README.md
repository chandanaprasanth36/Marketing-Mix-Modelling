# Marketing-Mix-Modelling
Marketing Mix Modelling project using Python, regression, ad stock, saturation and sales data.
# Marketing Mix Modelling for an E-commerce Brand

## Project Overview
This project explores the relationship between marketing channels and sales revenue using Python and regression analysis.

It uses a synthetic 104-week dataset to demonstrate Marketing Mix Modelling (MMM), advertising carryover (adstock), saturation, seasonality, model evaluation and preliminary marketing channel contribution analysis.

## Business Objective
To explore how Google Ads, Meta Ads, TV advertising and promotional activities relate to sales revenue.

## Tools Used
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Linear Regression

## Dataset
The dataset includes weekly marketing spend, promotional activity and sales revenue over 104 weeks.

**Note:** The data is synthetic and is used only for learning and portfolio demonstration.

## Methodology
1. Created and explored the dataset.
2. Visualised sales trends and marketing spend.
3. Built a baseline regression model.
4. Built an improved model using adstock, saturation and seasonality.
5. Evaluated the models using MAE, RMSE and R².
6. Explored estimated channel contribution and preliminary ROAS.

## Model Results
The improved model achieved the following results on the chronological test period:

| Metric | Result |
|---|---:|
| MAE | ₹4,787.38 |
| RMSE | ₹5,538.71 |
| R² | 0.484 |

## Limitations
- The dataset is simulated, not actual business data.
- Channel contribution and ROAS estimates are exploratory and are not proof of causal impact.
- Real-world MMM requires reliable campaign data and further validation.

## Key Learnings
- Exploratory data analysis
- Regression modelling and evaluation
- Adstock and saturation concepts
- Seasonality analysis
- Marketing contribution and ROAS fundamentals

## Project Files
- `mmm_marketing_data.csv` — marketing dataset
- `.ipynb` file — Python notebook containing analysis and modelling

## Disclaimer
This is an independent learning project using synthetic data. It does not represent any real brand's marketing performance.
