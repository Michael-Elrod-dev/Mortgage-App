# Mortgage App

This is a banking application coded in Java, it includes a couple of important classes, namely `Customer` and `Mortgage`.

## Classes

### `Customer`

This class extends the `AbsCustomer` abstract class and implements the `ICustomer` interface. It represents a bank customer and stores their properties like name, monthly debt payments, income, and credit score. It also includes methods for applying for a loan, retrieving the rate, retrieving monthly payment, and accessing basic customer information. 

### `Mortgage`

The `Mortgage` class extends the `AbsMortgage` abstract class and implements the `IMortgage` interface. It represents a mortgage loan with properties like number of payments, interest rate, principal amount, and details about the customer associated with this mortgage. 

This class also includes several methods such as `loanApproved` which checks the approval status of the loan, `getPayment` which returns the monthly payment on the loan, `getRate` which calculates the interest rate based on several factors, `getPrincipal` to get the principal loan amount, and `getYears` to get the duration of the loan in years. 

## How to use this application

This application serves as a model for the banking system and does not have a user interface for direct interaction. It should be integrated into a larger banking application with a proper user interface.

To use these classes, you'll first need to instantiate a `Customer` object with the required properties like name, monthly debt payments, income, and credit score. Once you have a `Customer` object, you can apply for a mortgage using the `applyForLoan` method, providing details like the down payment, the cost of the house, and the loan duration in years. 

The `Mortgage` object, once created, allows you to check if the loan is approved, get the monthly payment, interest rate, principal loan amount, and the duration of the loan in years.
