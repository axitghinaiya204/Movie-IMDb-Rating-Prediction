# Movie IMDb Rating Prediction using Regression and Machine Learning

## Project Overview

This project focuses on predicting IMDb movie ratings using Regression Modeling and Machine Learning algorithms.

The main objective is to understand how different movie-related factors, such as production budget, movie duration, audience votes, critic reviews, and social media popularity, influence a movie's IMDb rating.

The project follows a complete Machine Learning workflow, including data understanding, exploratory data analysis, data preprocessing, feature engineering, regression modeling, machine learning, model evaluation, and model interpretation.

## Problem Statement

To develop predictive models that estimate a movie's IMDb rating based on its cinematic and audience engagement features.

The project compares traditional statistical regression techniques with machine learning algorithms to identify effective prediction methods.

## Dataset Information

- **Dataset:** IMDb Movie Metadata Dataset
- **Original observations:** 5,043 movies
- **Original features:** 28 columns
- **Target variable:** `imdb_score`
- **Problem type:** Regression

### Selected Features

The project initially selects seven independent variables:

1. Duration
2. Budget
3. Number of critic reviews
4. Director Facebook likes
5. Cast total Facebook likes
6. Number of voted users
7. Movie Facebook likes

The target variable is `imdb_score`.

## Technologies and Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- SciPy
- SHAP

## Project Workflow

1. Data Understanding
2. Exploratory Data Analysis (EDA)
3. Missing Value Identification and Treatment
4. Outlier Detection and Treatment
5. Feature Scaling using StandardScaler
6. Feature Engineering
7. Data Visualization
8. Regression Modeling
9. Statistical Hypothesis Testing
10. Machine Learning Model Building
11. Hyperparameter Tuning
12. Feature Selection
13. Model Evaluation
14. SHAP Analysis

## Machine Learning Algorithms

The following models are implemented and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Voting Regressor

## Model Evaluation Metrics

The models are evaluated using:

- R-squared (R²)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

### Reported Results

The project report records the following Random Forest baseline results:

| Metric | Result |
|---|---:|
| R² Score | 0.3691 |
| MAE | 0.6810 |
| RMSE | 0.9296 |

These are reported baseline results; performance may vary when the notebook is rerun.

## Project Files

- `movie_imdb_rating_prediction.ipynb` – Complete Python implementation.
- `project_report.pdf` – Detailed project documentation and analysis.

## Installation and Usage

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Movie-IMDb-Rating-Prediction.git
```

### 2. Navigate to the project directory

```bash
cd Movie-IMDb-Rating-Prediction
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Add the dataset

Place `movie_metadata.csv` inside the `data` folder.

The dataset should be obtained from its original source, subject to its applicable terms.

### 5. Run the project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open `movie_imdb_rating_prediction.ipynb` and run the notebook cells.

## Project Outcomes

- Analyzed IMDb movie metadata.
- Identified important factors associated with movie ratings.
- Applied statistical regression techniques.
- Compared multiple machine learning algorithms.
- Evaluated model performance using regression metrics.
- Applied feature selection and hyperparameter tuning.
- Used SHAP to interpret model predictions.

## Conclusion

This project demonstrates the application of statistical regression and machine learning techniques to predict IMDb movie ratings. It also provides insights into the relationship between movie characteristics, audience engagement, and movie ratings.

## Author

**MSc Data Science Student**

**Project:** Regression Modeling and Machine Learning

**Project Title:** Movie IMDb Rating Prediction using Regression and Machine Learning


