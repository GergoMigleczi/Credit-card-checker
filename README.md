# Credit-card-checker

In this project, I had the role of a clerk who checks if credit cards are valid.

### Tasks:

1. Create a function, validateCred() that has a parameter of an array. The purpose of validateCred() is to return true when an array contains digits of a valid credit card number and false when it is invalid. This function should NOT mutate the values of the original array. To find out if a credit card number is valid or not, use the Luhn algorithm.

2. Create another function, findInvalidCards() that has one parameter for a nested array of credit card numbers. The role of findInvalidCards() is to check through the nested array for which numbers are invalid, and return another nested array of invalid cards.

3. Create a function, idInvalidCardCompanies() that has one parameter for a nested array of invalid numbers and returns an array of companies, which released invalid cards.

* First Digit	+ Company
* 3           + Amex (American Express)
* 4	          + Visa
* 5	          + Mastercard
* 6	          + Discover

