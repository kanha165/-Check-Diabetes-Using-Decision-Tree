# Medical Diagnosis Prediction using Decision Tree (All-in-One)

This project predicts whether a patient is likely to have **Diabetes** based on their medical parameters using a **Decision Tree Classifier**. The prediction is displayed as a **colored circle** with the result text inside for easy visualization.

---

## Project Structure

decision tree classifier/
│
├── diabetes.csv # PIMA Indians Diabetes dataset
├── train_model
├── diabetes_model.pkl # Saved trained model (auto-generated)
├──test_model
└── README.md # Project description

---

## 🧰 Tools & Libraries

- **Python 3.x**
- **pandas** – Data handling
- **numpy** – Array manipulation
- **scikit-learn** – Decision Tree Classifier
- **matplotlib** – Graphical output (colored circle)
- **Jupyter Notebook / VS Code / PyCharm** – Development environment

---

## 📊 Dataset

**PIMA Indians Diabetes Dataset** from Kaggle:

- **Link:** [https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Features:**
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
- **Target:** Outcome (0 = Not Diabetes, 1 = Diabetes)

---

## ⚙️ How to Run

### 1️⃣ Run the All-in-One Python File

```bash
python test_model.py


Step 1: The model is trained automatically on the dataset.

Step 2: Model accuracy, confusion matrix, and classification report are displayed.

Step 3: Model is saved as diabetes_model.pkl.

Step 4: You will be prompted to enter patient medical details:

Number of Pregnancies

Glucose Level

Blood Pressure

Skin Thickness

Insulin Level

BMI

Diabetes Pedigree Function

Age

Step 5: The prediction is displayed graphically as a colored circle:

Red Circle → Diabetes

Green Circle → Not Diabetes / Safe

The text inside the circle also shows the result.



 References

Scikit-learn Decision Tree Documentation

PIMA Indians Diabetes Dataset on Kaggle

Python matplotlib library for visualization


**Author**
Kanha Patidar – B.Tech CSIT Student
Indore, India


```
