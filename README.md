Hi, I'm Neelkamal, and this is my machine learning project where I built a model to predict
a person's **creditworthiness** based on their financial and demographic information. 
The goal is to automate the decision-making process for loan approvals using real-world-style data and practical ML techniques.


Objective
The main aim of this project is to predict whether a loan applicant is **creditworthy or not** using classification models.
This helps in making faster and more informed decisions in finance, especially for banks and lending platforms.


Problem Type

- **Supervised Machine Learning**
- **Binary Classification**
- Target variable: `Creditworthy` (1 = Yes, 0 = No)


Features Used

The features I selected reflect factors that impact a person’s ability to repay a loan. These include:

| Feature                         | Why it Matters                                     |
|---------------------------------|----------------------------------------------------| 
| `AnnualIncome`, `MonthlyIncome` | How much the person earns                          |
| `LoanAmount`, `LoanDuration`    | How much loan is being asked for, and for how long |
| `CreditScore`                   | Past credit performance                            |
| `DebtToIncomeRatio`             | Existing financial burden                          |
| `MonthlyLoanPayment`            | EMI impact on income                               |
| `EmploymentStatus`, `EducationLevel`, `JobTenure` | Stability of job & income        |
| `MaritalStatus`, `Dependents`   | Personal responsibilities                          |
| `HomeOwnershipStatus`           | Asset ownership                                    |
| `PreviousLoanDefaults`, `BankruptcyHistory` | Past financial behavior                |
| `SavingsAccountBalance`, `TotalAssets`, `NetWorth` | Overall financial strength      |


ML Approach
I used the following steps to build and evaluate the model:

1. Cleaned and filtered the dataset
2. Encoded categorical variables
3. Engineered features like `NetWorth`, `MonthlyLoanPayment`, `TotalDebtToIncomeRatio`
4. Trained a **Random Forest Classifier**
5. Evaluated with:
   - ROC-AUC
   - Confusion Metrices






