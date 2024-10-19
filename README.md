# Date_A_Scientist
Supervised Machine Learning Capstone Project
# Project Overview
----
The notebook focuses on exploring OKCupid user profile data, performing data cleaning, and building machine learning models to predict user characteristics like their behavior or preferences based on their demographic and textual data. The project's primary objective was to apply machine learning techniques to predict a user's astrological sign using their preferences for social vices (such as drinking, drugs, etc.,).
After exploring the base project statement, we also used classification, regression, and ensemble machine-learning techniques to predict users' sex and reported the respective accuracy/precision metrics.

- - - -
# Main Steps in the Project:
## 1. Data Import:

The dataset consists of multiple features related to users' age, body type, dietary preferences, education, and a series of personal essays.
Missing values are handled, and data types are explored.

## 2. Data Exploration & Profiling:

Analysis of data completeness, feature distributions, and initial inspection of categorical and numerical features (e.g., age, height, income, orientation).

## 3. Feature Engineering:

Processing categorical features like body_type, ethnicity, and essays (text data) to make them suitable for machine learning models.
Transformations include encoding categorical variables and handling missing data.

## 4. Modeling and Machine Learning:

Supervised learning techniques are applied using features such as user demographics, lifestyle, and preferences.
Scaling and preprocessing steps are performed to improve model performance.

## 5. Evaluation:

Model performance is evaluated using standard metrics such as accuracy, precision, recall, and F1-score.

- - - -
# Technologies & Libraries Used:
* Pandas, NumPy: Data manipulation and exploration.
* Matplotlib, Seaborn: Data visualization.
* scikit-learn: Machine learning model building, feature scaling, and evaluation.

- - - - 
# Instructions:
* Clone the repository.
* Install dependencies using pip install -r requirements.txt.
* Open the Jupyter notebook and run the cells sequentially to reproduce the analysis and modeling steps.

- - - - 
# Future Work:
* Enhance feature engineering with more advanced natural language processing (NLP) for essay data.
* Try alternative models to further improve prediction accuracy.
