# Loan_Assistant
Loan Assistant is a project made using Java Swing it will help you to get handle on consumer debt. By this project you can compute payments and loan terms by using given balance and interest rate information. Here I have added focus traversal among controls , how to do input validation, and the message box for user feedback. 

It uses four labels and textfield for taking the input from users i.e Loan amount,Rate of interest,Number of payment and monthly amount to be paid.

GridBagLayout is used to place the labels,textfield , buttons and other swing controls.

This project works in two mode

*It calculates number of payment one should do after entering the Loan amount,Rate of Interest and Monthy Payment(Compute No of Payment)

*It calculates Monthy payment one have to pay(Compute Payment)

On computing one of the above mode output of Compute Payment or No of months is displayed in the TextArea field like detailed information is shown. 

For validating the input, so that the user don't type any other character excluding numbers from(0-9) this is done using validateDecimalNumber()

The focus is transferred from one field to other textField using Enter and Tab button by using transferFocus()

* Functions performed

* Computing Monthly Payment

* Computing Number of Payments

* Loan Analysis

* New Loan Analysis

* Zero Interest Condition

* Focus Transfer(Tab)

* Input Validation(Numbers)

* Confirm Dialog(To notify users about wrong or empty input)

* User Messages(Alert user about minimum payment) 
