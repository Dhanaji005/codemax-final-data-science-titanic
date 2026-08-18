# 🚢 Codemax Final Data Science Project – Titanic Survival Prediction

## 📌 Project Overview

This project was developed as the **Module 6 – Final Data Science Project** for the Codemax Digital internship.

The project follows an end-to-end Data Science and Machine Learning workflow using the classic Titanic passenger dataset.

The objective is to analyze passenger information and build classification models to predict whether a passenger survived.

## 🎯 Objectives

- Understand and clean the dataset
- Perform Exploratory Data Analysis (EDA)
- Create meaningful visualizations
- Handle missing values
- Encode categorical variables
- Scale numerical variables
- Train machine-learning classification models
- Evaluate model performance
- Compare Logistic Regression and Random Forest
- Identify important predictive features
- Present final analytical insights

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## 📊 Dataset

The project uses the Titanic dataset available through the Seaborn library.

Main features:

- `pclass` – Passenger class
- `sex` – Gender
- `age` – Age
- `sibsp` – Siblings/spouses aboard
- `parch` – Parents/children aboard
- `fare` – Passenger fare
- `embarked` – Port of embarkation
- `alone` – Whether passenger travelled alone

Target:

- `survived` – Survival status

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Feature Selection
   ↓
Preprocessing Pipeline
   ↓
Train/Test Split
   ↓
Machine Learning
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Feature Importance
   ↓
Final Insights & Conclusion
```

## 🤖 Machine Learning Models

### 1. Logistic Regression
Used as an interpretable baseline binary classification model.

### 2. Random Forest Classifier
Used to capture non-linear relationships and provide feature importance.

The notebook automatically compares both models using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

The model with the best F1 Score is selected as the final model.

## 📈 Exploratory Analysis

The notebook includes:

- Survival distribution
- Survival rate by gender
- Survival rate by passenger class
- Age distribution
- Fare distribution
- Correlation heatmap
- Feature importance
- Model performance comparison
- Confusion matrix
- ROC curve

## 💡 Key Insights

The analysis investigates relationships between survival and passenger characteristics. Gender, passenger class and fare are especially useful predictive variables, while age and family-related information provide additional signals.

The exact model scores should be taken from the executed notebook because results can vary slightly across dataset versions and environments.

## ▶️ How to Run

### Google Colab

1. Open the `.ipynb` file in Google Colab.
2. Run the cells from top to bottom.
3. Check that all outputs and visualizations are generated.
4. Save the executed notebook.

### Local Jupyter Notebook

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Then open:

```text
Codemax_Final_Data_Science_Project_Titanic.ipynb
```

## 📁 Repository Structure

```text
codemax-final-data-science-titanic/
│
├── Codemax_Final_Data_Science_Project_Titanic.ipynb
├── README.md
└── requirements.txt
```

## 🎓 Internship Deliverables

This project is prepared for the Codemax Digital Module 6 final submission:

- GitHub Repository Link
- Google Colab Notebook Link
- LinkedIn Post Link

## 👨‍💻 Author

**Dhanaji Mali**

BCA Graduate | Python | Java | SQL | Data Science | Machine Learning

---

⭐ If you find this project useful, feel free to explore the notebook and connect with me on LinkedIn.
