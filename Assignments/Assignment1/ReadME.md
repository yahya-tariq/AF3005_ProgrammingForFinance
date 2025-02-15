Smart Financial Management System - Assignment 1

Overview

This repository contains the implementation of Assignment 1 for the Smart Financial Management System. The assignment consists of five interactive financial tools using Jupyter Notebook and ipywidgets. These tools assist users in evaluating loan eligibility, assessing stock risks, tracking loan repayments, monitoring stock prices, and following exchange rate trends.

Features & Tasks

1. Loan Eligibility Checker

Determines loan eligibility based on employment status, income, and credit score.

Uses toggle buttons for employment selection and integer inputs for income and credit score.

Provides an interest rate or rejection reason based on user inputs.

2. Investment Risk Assessment

Evaluates the risk level of investments based on historical stock returns.

Uses a Textarea input where users enter stock returns separated by commas.

Categorizes returns as High, Medium, or Low Risk.

3. Loan Repayment Tracker

Simulates monthly loan repayments until the loan is fully paid.

Uses integer inputs for loan amount and monthly payment.

Displays the remaining balance month by month.

4. Stock Price Monitoring

Tracks stock prices and advises when to sell if prices exceed PKR 200.

Uses Textarea input where users enter daily stock prices.

Identifies the day when stock prices reach PKR 200.

5. Currency Exchange Rate Tracker

Monitors exchange rate fluctuations from a starting value to a target value.

Uses integer inputs for starting rate and target rate.

Displays daily exchange rate progression until the target rate is reached.

Implementation - ipywidgets

ipywidgets is used in this project to create interactive widgets in Jupyter Notebook. Below is how different widgets are implemented:

User Input Widgets:

ToggleButtons: Used for selecting employment status in Task 1.

IntText: Used for numerical inputs like income, credit score, loan amount, and monthly payment.

Textarea: Used for entering multiple stock prices and investment returns.

Displaying Output:

Output(): Captures and displays formatted results.

print(): Used within the Output() widget to display messages and computed results.

Button Click Events:

Button(): A submit button is created for each task.

on_click(): Defines a function that triggers calculations and displays results when clicked.
