
# IPL Match Winner Prediction using Scikit-learn

This project is part of the CS506 Team Project Submission #2. It applies various machine learning techniques using the Scikit-learn library to predict the winner of IPL matches based on historical data.

## Dataset
- Source: Kaggle (IPL All Season Summary)
- File: `all_season_summary.csv`
- Features Used: `home_team`, `away_team`, `toss_won`, `venue_name`
- Target: `winner`

## Models Used
### Supervised Learning
- **Random Forest Classifier**
- **Logistic Regression**

### Unsupervised Learning
- **KMeans Clustering**

## Evaluation
- Accuracy score
- Confusion matrix (heatmap visualization)

## Feature Engineering
- Label encoding of categorical features
- Missing value handling
- Train/Test data split (80/20)

## Insights
- Venue and toss result are key predictors of match outcome
- Random Forest performed better than Logistic Regression
- KMeans clustering revealed performance-based groupings

## Tools & Libraries
- Python
- Scikit-learn
- Pandas
- Matplotlib & Seaborn

## Contributors
Team09 – Ashwin, Akarsh, Divakar, Sara

## License
This project is for academic purposes only.
