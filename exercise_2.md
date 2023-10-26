## Machine Problem: Monthly Expenses Tracker

**Objective:**  
Write a Python function named `expenses_tracker` that calculates a person's monthly expenses and determines if they are within their monthly budget.

**Instructions:**

1. The function will accept two arguments:
    - A dictionary of expenses where the key is the name of the expense and the value is the cost. For instance: `{"Rent": 1000, "Groceries": 200, "Entertainment": 50}`.
    - The monthly budget (a numerical value).
2. Use variables to keep track of the total expenses.
3. Calculate the total expenses by summing up all the values in the dictionary.
4. Use `if`, `elif`, and `else` to determine the status of the monthly budget:
    - If total expenses are equal to the budget: "On Budget"
    - If total expenses are less than the budget: "Under Budget by `$amount`"
    - If total expenses are more than the budget: "Over Budget by `$amount`"
5. The function should return the status of the budget along with the amount if applicable.
