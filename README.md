Bank Marketing Campaign – Machine Learning Project


[Presentation](https://www.canva.com/design/DAHCyuRpQgI/55C1TMiS6f19Em2vIRiAxQ/edit?utm_content=DAHCyuRpQgI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

**Project Overview**
- This project aims to develop a machine learning model to predict whether a bank customer will subscribe to a term deposit product based on demographic and marketing campaign data.
- The goal is to improve the effectiveness of telemarketing campaigns by identifying customers who are more likely to subscribe, thereby reducing operational costs and increasing conversion rates.

**Business Problem**

- Banks conduct telemarketing campaigns to promote term deposit products. However, not all contacted customers are interested, leading to inefficient use of time and resources.

**Key challenges:**

1. Low conversion rate
2. High operational cost of telemarketing
3. Lack of data-driven targeting strategy

This project builds a predictive model to support marketing decision-making.

**Dataset Information**

T| Feature  | Description                        |
| -------- | ---------------------------------- |
| age      | Customer age                       |
| job      | Type of job                        |
| balance  | Average yearly balance             |
| housing  | Housing loan status                |
| loan     | Personal loan status               |
| contact  | Communication type                 |
| month    | Last contact month                 |
| campaign | Number of contacts during campaign |
| pdays    | Days since last contact            |
| poutcome | Outcome of previous campaign       |
| deposit  | Target variable (0 = No, 1 = Yes)  |

**Analytical Approach**

**- Problem Type:** Supervised Learning
**- Task:** Binary Classification
**Target Variable:** deposit

**Evaluation Metrics:**
- Recall
- Precision
- F1-Score
Recall is emphasized due to business priority in minimizing missed potential depositors.

**Data Preparation**

Data Cleaning
- Removed duplicate records
- Replaced pdays = -1 with 0
- Validated data types
- No missing values found

**Feature Engineering**
- Binary encoding of target variable
- One-Hot Encoding for categorical variables
- Standard Scaling for numerical variables
- Model selection based on cross-validation and evaluation metrics.


**Model Deployment**

The final selected model is saved using Pickle format and can be integrated into a decision-support system for marketing prioritization.


Author
Madina Febriani 
Capstone Project – Machine Learning