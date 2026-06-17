# 🚢 Titanic Survival Prediction using Decision Tree Classifier

## 📌 Project Overview

This machine learning project predicts whether a passenger survived the Titanic disaster using a Decision Tree Classifier. The project includes data preprocessing, feature engineering, model training, pruning techniques, evaluation, and visualization.

---

## 📂 Dataset

- Dataset: Titanic Dataset (Seaborn)
- Target Variable: `survived`

### Features Used
- Passenger Class (`pclass`)
- Gender (`sex`)
- Age (`age`)
- Fare (`fare`)
- Embarkation Port (`embarked`)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-Learn

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Handled missing values using `SimpleImputer`
- Encoded categorical variables using `LabelEncoder`

### 2. Feature Selection
Selected relevant features affecting passenger survival.

### 3. Train-Test Split
- 80% Training Data
- 20% Testing Data

### 4. Model Training
Implemented:
```python
DecisionTreeClassifier()
```

### 5. Pre-Pruning
Applied:
- max_depth
- min_samples_split

to reduce overfitting.

### 6. Post-Pruning
Implemented Cost Complexity Pruning using:

```python
ccp_alpha
```

### 7. Model Evaluation
Evaluated model performance using:
- Accuracy Score

### 8. Visualization
Visualized the trained decision tree using:

```python
plot_tree()
```

---

## 📈 Results

The model successfully predicts passenger survival and demonstrates how pruning techniques improve model generalization.

---

## 🎯 Learning Outcomes

- Data Cleaning
- Missing Value Imputation
- Label Encoding
- Decision Tree Classification
- Hyperparameter Tuning
- Pre-Pruning
- Post-Pruning
- Model Evaluation
- Tree Visualization

---

## 🚀 Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ Run the Project

```bash
jupyter notebook
```

Open:

```bash
decision_tree_on_titanic_dataset.ipynb
```

---

## 🔮 Future Improvements

- Random Forest Classifier
- XGBoost Classifier
- Gradient Boosting
- GridSearchCV Hyperparameter Tuning

---

## 👨‍💻 Author

Ashutosh Mehta

Computer Engineering Student
