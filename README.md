# Expense_Tracker
This Expense Tracker program allows users to record, view, and analyze their expenses by category. It provides functions to add, display, and analyze expenses, helping users monitor their spending habits. Here's an overview of each function
add_expense(expenses):

Prompts the user to enter the expense amount, description, and category.
Adds a dictionary with these details to the expenses list.
Handles invalid inputs by checking if the entered amount is numeric.
view_expenses(expenses):

Displays all recorded expenses in a clear, enumerated list format.
Shows each expense's description, amount, and category.
Informs the user if there are no expenses to view.
analyze_expenses(expenses):

Analyzes the total amount spent in each category.
Aggregates and displays total expenses for each category.
main():

Provides a menu for the user to choose between adding, viewing, or analyzing expenses, or exiting the program.
Continues running until the user decides to exit.
