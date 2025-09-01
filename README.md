## Titanic-Survival-Prediction

# Project Overview
  This project uses Machine Learning to predict whether a passenger survived the Titanic disater.
  We use Python libraries like NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn to explore the       dataset, clean it, visualize trends, and build ML models.
# dataset
  The dataset comes from the Kaggle Titanic Competition
  Titanic-Dataset.csv

  Features include:
    i) Passenger id
   ii) Name
  iii) Passenger class(Pclass)
   iv) Gender
    v) Age
   vi) Number of siblings/spouses(SibSp)
  vii) Number of parents/children (ParCh)
 viii) Fare paid (Fare)
   ix) Embarked port (Embarked)
    x)  Survival status (Survived)

# Steps in the project
  1. Data Loading -> Read CSV file with Pandas.
  2. Exploratory Data Analysis (EDA) -> Visualize survival trands by gender, age, and class.
  3. Data Cleaning -> Handle missing values, drop unnecessary columns and encode categorical data.
  4. Feature Engineering -> Create meaningful features (e.g., FamilySize).
  5. Model Training -> Train Logistic Regression, Decision Tree, and Random Forest.
  6. Model Evaluation -> Compare models using accuracy, confusion_matrix, and classification report.

# Machine Learning Models Used
  1. Logistic Regression
  2. Decision Tree
  3. Random Forest

# Results
  The models were evaluated on test data, and perfomance was measured using:
  1. Accuracy
  2. Confusion Matrix
  3. Precision, Recall, F1-Score

# How to Run
1. Clone the repo:
   git clone https://github.com/BhageshSM2005/Titanic-Survival-Prediction.git
2. Install dependencies:
   pip install numpy pandas matplotlib seaborn scikit-learn
3. Run the Jupyter Notebook:
   jupyter notebook titanic.ipynb
