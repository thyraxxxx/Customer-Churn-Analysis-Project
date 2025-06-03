# Customer Churn Analysis Project

This project aims to analyze customer churn behavior using a combination of data transformation, exploratory analysis, predictive modeling, and visualization techniques. It follows a hands-on data science pipeline inspired by the tutorial by Codebasics: [Customer Churn Prediction](https://www.youtube.com/watch?v=QFDslca5AX8).

## Objective

To identify key patterns that lead to customer churn and develop a predictive model that classifies customers as likely to churn or stay. The results can help businesses proactively address churn and improve retention strategies.

---

## Tools & Technologies

- **Power BI** – Dashboard creation and visualization
- **SQL Server Management Studio** – Data cleaning, view creation, transformation
- **Excel** – Raw data handling, pre-processing
- **Jupyter Notebook (Python 3)** – Modeling using Random Forest, encoding, and prediction
- **Pandas, NumPy, Scikit-learn, Matplotlib** – Python libraries for data science


---

## Key Tasks Performed

- **Data Cleaning:** Used SQL to handle NULLs, structure data, and create production views
- **Exploratory Analysis:** Identified key variables like gender, contract type, and churn category through group-by queries
- **Feature Engineering:** Encoded categorical variables and handled missing values using Python
- **Model Building:** Trained a Random Forest model to predict churn status
- **Reporting:** Created a comprehensive Power BI report showing churn trends and metrics
- **Deployment:** Prepared new customer data for prediction and evaluated model performance

---

## Key Insights

- Customers with short tenure and month-to-month contracts showed higher churn rates
- Streaming services and premium support had moderate correlation with churn likelihood
- The model achieved high accuracy using simple tree-based classification

---

## How to Run This Project

1. Load the data into SQL Server and run the SQL scripts from the `SQL_Queries/` folder.
2. Open `churn_analysis.ipynb` in Jupyter to run the predictive model.
3. Use Power BI to load the `Churn_Analysis_Report.pbix` and explore visuals.
4. Upload new customer data into `Prediction_Data.xlsx` to generate future predictions.

---

## Contact

Feel free to reach out if you have questions or suggestions!

