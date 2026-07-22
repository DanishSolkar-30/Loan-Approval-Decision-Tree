# 🏦 Loan Approval Prediction using Decision Tree

## 📌 Project Overview

This project predicts whether a customer's loan application will be **Approved** or **Rejected** using the **Decision Tree Classification** algorithm. The model analyzes customer information such as **Age, Monthly Income, Credit Score, Employment Status, and Existing Loan Status** to make predictions.

The project also evaluates the model using common classification metrics and visualizes the trained Decision Tree, making it easier to understand how the model reaches its decisions.

---

## 🚀 Features

* Predicts loan approval based on customer details.
* Uses the Decision Tree Classification algorithm.
* Encodes categorical data using Label Encoding.
* Splits the dataset into training and testing sets.
* Evaluates model performance using:

  * Accuracy Score
  * Confusion Matrix
  * Classification Report
* Accepts real-time user input for prediction.
* Displays the trained Decision Tree visualization.

---

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib

---

## 📂 Dataset

The dataset (`data.csv`) contains the following attributes:

| Feature           | Description                                         |
| ----------------- | --------------------------------------------------- |
| Age               | Applicant's age                                     |
| Monthly_Income    | Monthly income of the applicant                     |
| Credit_Score      | Credit score of the applicant                       |
| Employment_Status | Employment status (Employed/Unemployed)             |
| Existing_Loan     | Whether the applicant has an existing loan (Yes/No) |
| Loan_Approved     | Target variable (Approved/Rejected)                 |

---

## ⚙️ How the Project Works

1. Load the dataset using Pandas.
2. Convert categorical values into numerical values using Label Encoding.
3. Select the input features and target variable.
4. Split the dataset into training and testing sets.
5. Train the Decision Tree Classifier using the Gini criterion.
6. Evaluate the model using Accuracy Score, Confusion Matrix, and Classification Report.
7. Accept customer details from the user.
8. Predict whether the loan application will be approved or rejected.
9. Display the Decision Tree visualization.

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Loan-Approval-Decision-Tree.git
```

Move into the project folder:

```bash
cd Loan-Approval-Decision-Tree
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python Loan_Approval_Decision_Tree.py
```

---

## 📊 Sample Input

```
Age: 28
Monthly Income: 50000
Credit Score: 750
Employment Status: 1
Existing Loan: 0
```

## ✅ Sample Output

```
Result : Loan Approved
```

---

## 📈 Evaluation Metrics

The model is evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## 📚 Learning Outcomes

This project helped me understand:

* Decision Tree Classification
* Gini Index
* Data Preprocessing
* Label Encoding
* Train-Test Split
* Model Training
* Model Evaluation
* Classification Metrics
* User Input Prediction
* Decision Tree Visualization

---

## 👨‍💻 Author

**Danish Solkar**

🎓 Computer Engineering Student
---

## If you found this project helpful, feel free to ⭐ the repository and connect with me on LinkedIn.
