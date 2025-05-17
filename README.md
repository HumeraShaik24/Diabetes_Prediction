# 🩺 Diabetes Prediction – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **exploratory data analysis (EDA)** on a diabetes dataset using Python. The goal is to understand trends and differences in medical attributes between diabetic and non-diabetic patients. No machine learning models are implemented — the focus is on deriving **insights through clean, effective analysis**.

> 🔬 *A foundational healthcare analytics project designed to inform future predictive modeling.*

---

## 🧪 Dataset Features

| 🔹 Feature                | 📝 Description                                   |
|--------------------------|--------------------------------------------------|
| `Pregnancies`            | Number of times pregnant                         |
| `Glucose`                | Plasma glucose concentration                     |
| `BloodPressure`          | Diastolic blood pressure (mm Hg)                 |
| `SkinThickness`          | Triceps skinfold thickness (mm)                  |
| `Insulin`                | 2-Hour serum insulin (mu U/ml)                   |
| `BMI`                    | Body Mass Index                                  |
| `DiabetesPedigreeFunction` | Genetic predisposition to diabetes              |
| `Age`                    | Patient's age in years                           |
| `Outcome`                | Diabetes diagnosis (1 = Diabetic, 0 = Non-Diabetic) |

---

## 📊 Key Insights

🧠 After grouping by `Outcome`, we found:

| Feature              | 🧍 Non-Diabetic (0) | 🧑‍⚕️ Diabetic (1) |
|----------------------|--------------------|------------------|
| Pregnancies          | 3.29               | 4.87             |
| Glucose              | 109.90             | 141.26           |
| BloodPressure        | 68.18              | 70.82            |
| SkinThickness        | 19.66              | 22.16            |
| Insulin              | 68.79              | 100.34           |
| BMI                  | 30.30              | 35.14            |
| DiabetesPedigreeFunc | 0.43               | 0.55             |
| Age                  | 31.19              | 37.07            |

📈 **Conclusion**:
- Diabetic patients show **significantly higher** values for Glucose, Insulin, BMI, and Age.
- Indicates strong correlation between these features and diabetes risk.

📌 This project forms a solid base for future predictive modeling (e.g., classification using ML).

---

## 🛠️ Tools & Technologies

| 🧰 Tool        | ⚙️ Purpose                   |
|---------------|------------------------------|
| **Python**     | Core programming language    |
| **Pandas**     | Data manipulation            |
| **NumPy**      | Numerical operations         |
| **Matplotlib** | Data visualization           |
| **Seaborn**    | Statistical plots            |
| **Jupyter Notebook** | Interactive development |

---

## 📁 Project Structure

📦 diabetes-eda
│
├── 📄 diabetes.csv # dataset
├── 📊 Diabetes prediction.ipynb # Main notebook with analysis
├── 🖼️ Visualizations # All the generated insights
├── 📄 README.md # Project documentation


---

## 🔮 Future Enhancements

- 🔄 Add Machine Learning models (Logistic Regression, Random Forest, etc.)
- 📏 Perform feature scaling and correlation matrix
- ⚖️ Address data imbalance using techniques like SMOTE
- 🧪 Model evaluation (Accuracy, ROC-AUC, F1-score)
- 📤 Export insights to PDF reports or interactive dashboards

---

## 👩‍💻 About Me

**Humera Shaik**  
📊 Data Analyst | 🔍 Insight Generator | 🤖 AI automation

📧 **Email**: humerah610@gmail.com  
📱 **Phone**: +91 7382273550  

🔗 [LinkedIn](www.linkedin.com/in/
humera-shaik-dataanalyst
) | 📄 [Resume]()

---

*Made with Passion and Python for data insight discovery.*



