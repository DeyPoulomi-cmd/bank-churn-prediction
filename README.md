# Bank Churn Prediction

This repository contains an advanced machine learning project focused on predicting customer churn for a bank. By leveraging data preprocessing, feature engineering, and machine learning algorithms, the project aims to identify high-risk customers and provide actionable insights to enhance customer retention strategies.

---

## Problem Statement

Banks face significant challenges in retaining customers in a highly competitive financial market. Identifying potential churners early can help design effective retention strategies, minimize revenue loss, and maintain a strong customer base.

---

## Objective

1. Predict customer churn based on behavioral and demographic attributes.
2. Identify the most significant features contributing to churn.
3. Provide actionable insights to improve retention strategies.

---

## Features of the Project

1. **Data Analysis**:
   - Explored key customer metrics, such as tenure, balance, and activity levels.
   - Visualized churn distribution and correlations between features.

2. **Preprocessing Pipeline**:
   - Handled missing values and encoded categorical variables (e.g., gender, geography).
   - Scaled numerical features like balance and credit score for model optimization.
   - Addressed class imbalance using oversampling techniques like SMOTE.

3. **Modeling**:
   - Implemented Logistic Regression, Random Forest, and Gradient Boosting models to predict churn.
   - Fine-tuned model hyperparameters using grid search for optimal performance.
   - Achieved the best performance with Gradient Boosting, obtaining an accuracy of 85%.

4. **Evaluation**:
   - Used precision, recall, F1-score, and ROC-AUC to evaluate model effectiveness.

---

## Insights and Learnings

1. **What did I learn?**
   - Customers with lower tenure and higher account balances are more likely to churn.
   - Balancing datasets and scaling features significantly improved model performance.
   - Gained expertise in applying ensemble methods for real-world classification problems.

2. **What did I try out?**
   - Tested multiple machine learning algorithms to identify the best-performing model.
   - Applied feature importance analysis to identify key factors driving churn.
   - Experimented with oversampling techniques to handle class imbalance effectively.

3. **What worked and why?**
   - Gradient Boosting achieved the best results due to its ability to handle non-linear relationships and feature interactions.
   - Preprocessing steps, such as scaling and encoding, ensured robust data inputs for models.
   - Hyperparameter tuning improved model generalization and reduced overfitting.

4. **Recommendations for the Business Counterpart**:
   - Focus retention efforts on customers with low tenure and high account balances, as they are at higher risk of churn.
   - Develop personalized engagement strategies for at-risk customers to improve satisfaction and loyalty.
   - Regularly update the dataset and retrain the model to adapt to evolving customer behaviors.

---

## Dataset

The dataset contains the following key attributes:
- **CustomerID**: Unique identifier for each customer.
- **CreditScore**: Credit score of the customer.
- **Geography**: Country of residence.
- **Gender**: Gender of the customer.
- **Tenure**: Number of years with the bank.
- **Balance**: Account balance.
- **NumOfProducts**: Number of products held by the customer.
- **HasCrCard**: Whether the customer has a credit card.
- **IsActiveMember**: Whether the customer is an active member.
- **EstimatedSalary**: Estimated annual salary.
- **Exited**: Target variable (1 = Churned, 0 = Retained).

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/bank-churn-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd bank-churn-prediction
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Run the Jupyter Notebook to explore the data and train models:
   ```bash
   jupyter notebook Bank_Churn_Prediction.ipynb
   ```

2. Evaluate the trained model:
   ```python
   from sklearn.metrics import classification_report

   y_pred = model.predict(X_test)
   print(classification_report(y_test, y_pred))
   ```

---

## Results

- **Accuracy**: 85%
- **Key Predictors**: Tenure, Balance, and Activity Level
- **Impact**: Improved customer retention targeting accuracy by 20%.

---

## Recommendations

1. Develop engagement strategies for customers with low tenure and high balances.
2. Personalize marketing efforts to retain at-risk customers.
3. Regularly update the dataset and retrain the model for consistent performance.

---

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- The dataset is provided by the bank's internal team.
- Thanks to the machine learning community for their valuable resources.

---

Thank you for exploring this project! If you have any questions or suggestions, feel free to reach out.
