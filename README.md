# Lending Club Case Study

## Table of Contents
* [General Info](#general-information)
* [Libraries Used](#libraries-used)
* [Conclusions-&-Considerations](#Conclusions-&-Considerations)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
>#### Introduction
In this case study, we are attempting to solve a real world business problem using Exploratory Data Science techniques. Also, we will develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

#### Business Understanding
A **consumer finance company**, which specialises in lending various types of loans to urban customers, when receives a loan application, has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
* If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given to us contains information about past loan applicants and whether they ‘defaulted’ or not. **The aim** is to identify patterns which indicate if a person is likely to **default**, which may be used for taking actions such as `denying the loan`, `reducing the amount of loan`, `lending (to risky applicants) at a higher interest rate`, etc.

#### Business Objective
**Company wants to understand the driving factors** (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

<a id='libraries-used'>## Conclusions & Considerations</a>
### Major Driving factor which can be used to predict the chance of defaulting and avoiding Credit Loss are:
* Annual Income
* Grade
* DTI
* Verification Status
* State

### Considerations
* More scrutiny while lending money to states like CA, FL, NY & TX
* Advisable to lend money after doing Source Verification
* Careful with Borrowers having high DTI value
* Scrutinize Borrowers who are having annual income in the range of 25K to 100K and who have 10+ years or less than 1 years of employments

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Libraries Used
- library - NumPy
- library - Pandas
- library - Matplotlib
- library - Seaborn
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@GeekGani]

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
