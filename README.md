# **Credit Card Dataset**

---

## *Context*
This case requires to develop a customer segmentation to define marketing strategy. The sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.

## *Content*

*Attribute Information:*

Following is the Data Dictionary for Credit Card dataset:

- CUSTID : Identification of Credit Card holder (Categorical)
- BALANCE : Balance amount left in their account to make purchases
- BALANCEFREQUENCY : How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
- PURCHASES : Amount of purchases made from account
- ONEOFFPURCHASES : Maximum purchase amount done in one-go
- INSTALLMENTSPURCHASES : Amount of purchase done in installment
- CASHADVANCE : Cash in advance given by the user
- PURCHASESFREQUENCY : How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
- ONEOFFPURCHASESFREQUENCY : How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
- PURCHASESINSTALLMENTSFREQUENCY : How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
- CASHADVANCEFREQUENCY : How frequently the cash in advance being paid
- CASHADVANCETRX : Number of Transactions made with "Cash in Advanced"
- PURCHASESTRX : Numbe of purchase transactions made
- CREDITLIMIT : Limit of Credit Card for user
- PAYMENTS : Amount of Payment done by user
- MINIMUM_PAYMENTS : Minimum amount of payments made by user
- PRCFULLPAYMENT : Percent of full payment paid by user
- TENURE : Tenure of credit card service for user

## *Source*

All of the information above was provided by Kaggle, to see more content about this case visit https://www.kaggle.com/arjunbhasin2013/ccdata

---

This analysis was created by [Guilherme Mattos](https://www.linkedin.com/in/guilhermefmattos/).

To access the analysis and modeling please open [`credit_card`](./notebooks/credit_card.ipynb) file inside the notebooks folder.

--- 

## **Table of Contents**

- [Notebook Contents](#Notebook-Contents)
- [Main Analysis](#Main-Analysis)
- [Modeling Technique Selection](#Modeling-Technique-Selection)
- [Results Discussion](#Results-Discussion)
- [Extra Contents](#Extra-Contents)

### **Notebook Contents**

| Sections |
| ------- |
| [0. Libraries](./notebooks/credit_card.ipynb/#0.-Libraries) |
| [1. Dataset](./notebooks/credit_card.ipynb/#1.-Dataset) |
| [2. Exploratory Analysis](./notebooks/credit_card.ipynb/#2.-Exploratory-Analysis) |
| [3. Feature Engineering](./notebooks/credit_card.ipynb/#3.-Feature-Engineering) |
| [4. Modeling](./notebooks/credit_card.ipynb/#4.-Modeling) |
| [5. Results](./notebooks/credit_card.ipynb/#5.-Results) |