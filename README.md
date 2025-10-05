# rent-calculator-in-python-project-
This project is a Python-based cost-sharing calculator designed to split the total monthly expenses among individuals living together in a shared room or flat. It collects essential inputs such as rent, food expenses, electricity usage, and number of people sharing the space, and calculates how much each person needs to contribute.
## Inputs we need from the user
# Total rent 
# Total food ordered for snacking
# Electricity units speed
# charge per unit
# Persons living in room/flat

## Output
# Total amount you've to pay is

rent = int(input("Enter your hostel/flat rent = "))
food = int(input("Enter the amount of food ordered = "))
electricity_spend = int(input("Enter the total of electricity spend ="))
charge_per_unit = int(input("Enter the charge per unit = "))
persons = int(input("Enter the number of persons living in room/flat = "))

total_bill = electricity_spend * charge_per_unit

output = (food + rent + total_bill ) // persons

print("Each person will pay = ", output )
