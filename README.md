# Python Expense Tracker Project

## Project Description:
The **Python Expense Tracker** application allows users to manage their expenses, track spending over time, and filter expenses by category. This simple **Python** command-line interface (CLI) app enables users to:
- Add new expenses
- View all expenses
- Calculate the total expense amount
- Filter expenses based on the specified category

It helps users organize their personal finances in an easy and straightforward way using Python.

## Features:
- **Add an Expense:** Users can input the amount and category of an expense.
- **List All Expenses:** Users can see all the expenses they’ve recorded.
- **Show Total Expenses:** Users can see the sum of all recorded expenses.
- **Filter Expenses by Category:** Users can view expenses that belong to a specific category.
- **Exit Program:** Ends the program.

## Functions:

1. **add_expense(expenses, amount, category):**
   - **Description:** Adds a new expense to the `expenses` list.
   - **Parameters:** 
     - `expenses`: List of expenses.
     - `amount`: The expense amount (float).
     - `category`: The category of the expense (string).
   - **Returns:** None.

2. **print_expenses(expenses):**
   - **Description:** Prints all the recorded expenses in a readable format.
   - **Parameters:**
     - `expenses`: List of expenses.
   - **Returns:** None.

3. **total_expenses(expenses):**
   - **Description:** Calculates the total of all recorded expenses.
   - **Parameters:**
     - `expenses`: List of expenses.
   - **Returns:** Total expense amount (float).

4. **filter_expenses_by_category(expenses, category):**
   - **Description:** Filters the expenses list based on the specified category.
   - **Parameters:**
     - `expenses`: List of expenses.
     - `category`: The category to filter by (string).
   - **Returns:** Filtered list of expenses by category.

5. **main():**
   - **Description:** The main function that runs the Expense Tracker application, presenting the user with options and performing actions based on their input.
   - **Returns:** None.

## How to Use:
1. Run the script in a Python environment.
2. The user will be presented with a menu of options:
   - **1:** Add a new expense.
   - **2:** List all expenses.
   - **3:** Show total expenses.
   - **4:** Filter expenses by category.
   - **5:** Exit the program.
3. Select the option by typing the corresponding number and follow the prompts.

