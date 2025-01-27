# eCommerce Transactions Analysis

## Project Overview
This project focuses on analyzing an **eCommerce Transactions Dataset** to derive actionable insights, build predictive models, and perform customer segmentation. It consists of three key tasks:  
1. **Exploratory Data Analysis (EDA)**  
2. **Lookalike Model Development**  
3. **Customer Segmentation using Clustering**

The project tests data analysis, machine learning, and business insight generation skills.

---

## Dataset Description
The dataset comprises three files:  
1. **Customers.csv**  
   - `CustomerID`: Unique customer identifier.  
   - `CustomerName`: Customer's name.  
   - `Region`: Continent where the customer resides.  
   - `SignupDate`: Customer registration date.  

2. **Products.csv**  
   - `ProductID`: Unique product identifier.  
   - `ProductName`: Product name.  
   - `Category`: Product category.  
   - `Price`: Price of the product (in USD).  

3. **Transactions.csv**  
   - `TransactionID`: Unique transaction identifier.  
   - `CustomerID`: Customer making the transaction.  
   - `ProductID`: Product involved in the transaction.  
   - `TransactionDate`: Date of the transaction.  
   - `Quantity`: Product quantity purchased.  
   - `TotalValue`: Total transaction value.  
   - `Price`: Product price during the transaction.  

---

## Tasks
### Task 1: Exploratory Data Analysis (EDA)
- Perform EDA to explore and analyze the dataset.  
- Derive **5 business insights** to inform company strategies.  
- Deliverables:  
  - **EDA Code**: `FirstName_LastName_EDA.ipynb`  
  - **Insights Report**: `FirstName_LastName_EDA.pdf`  

### Task 2: Lookalike Model
- Build a recommendation model to find 3 similar customers for each of the first 20 customers (`CustomerID: C0001 - C0020`).  
- Deliverables:  
  - **Lookalike Results**: `FirstName_LastName_Lookalike.csv`  
  - **Model Code**: `FirstName_LastName_Lookalike.ipynb`  

### Task 3: Customer Segmentation
- Perform clustering using customer profiles and transaction data.  
- Evaluate the clustering using the **DB Index** and other metrics.  
- Deliverables:  
  - **Clustering Report**: `FirstName_LastName_Clustering.pdf`  
  - **Clustering Code**: `FirstName_LastName_Clustering.ipynb`  


