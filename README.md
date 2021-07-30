# Data-Anonymization

This project is based on various standard anonymization techniques used to anonymize data.

Dataset Used: https://www.kaggle.com/mrferozi/loan-data-for-dummy-bank

## Techniques Used:
-K Anonymization

-Data Perturbation

-Data Swapping

-Data Pseudonymization


## Results

### 1. K-Anonymization

Data is anonymized on basis of home ownership, income category, loan condition and term of loan. There are atleast 18 different individuals who have the same set of attributes.

**Attributes affected:** None

<img src="Results/K%20Anonymization.JPG" width=500 height=500>

### 2. Data Perturbation

Noise has been added to loan borrowed and interest rate.

**Attributes affected:** Loan amount, Interest rate

<img src="Results/Data%20Perturbation.JPG" width=500 height=500>

### 3. Data Perturbation

Fake house numbers are generated and are added to the hometown.

**Attributes affected:** Region

<img src="Results/Data%20Pseudonymization.JPG" width=500 height=500>

### 4. Data Swapping

The year in which loan is borrowed is swapped.

**Attributes affected:** Year

<img src="Results/Data%20Swapping.JPG" width=500 height=500>




