
# Predicting clients who are leaving BetaBank

This project is the final part of the 'Supervised Learning' sprint at the TripleTen Data Science Bootcamp. The objective is to create a classification model that predicts clients who are leaving BetaBank, using information about clients who have already left and clients who remain in the bank. This includes features such as their credit score, gender, the number of products they possess in the bank, among other details. **The model is required to achieve an F1 score higher than 59% for the test dataset.**

## Description

### Features

* RowNumber — Row index
* CustomerId — Clients index
* Surname
* CreditScore — Between 0 and 1000
* Geography — Country
* Gender
* Age
* Tenure — The duration for which the account remains valid or active.
* Balance — Current balance in the bank account.
* NumOfProducts — Number of products that the client possesses in the bank.

* HasCrCard — 1: Yes; 0: No
* IsActiveMember — 1: Yes; 0: No
* EstimatedSalary — Estimated Salary

### Target

* Exited — 1: Not a client anymore; 0: Still an active client in the bank.