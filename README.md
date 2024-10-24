# Python-variables-and-control-flow-practice-PROJECT
# Variable Assignment & Arithmetic Operations
question1.py for Variable Assignment & Arithmetic Operations.
a = 10
b = 5

# Perform operations and print results
print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)
print("Division:", a / b)

# Odd or Even Checker
question2. py for Odd or Even Checker
number = int(input("Enter a number: "))

if number % 2 == 0:
    print(f"{number} is Even.")
else:
    print(f"{number} is Odd.")

    
# Grade Categorizer
question3. py for Grade Categorizer
score = int(input("Enter your score (0-100): "))

if 90 <= score <= 100:
    print("Grade: A")
elif 80 <= score < 90:
    print("Grade: B")
elif 70 <= score < 80:
    print("Grade: C")
elif 60 <= score < 70:
    print("Grade: D")
else:
    print("Grade: F")

 # Simple Calculator with Conditionals
 question4. py for Simple calculator with conditionals
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
operation = input("Enter an operation (+, -, *, /): ")

if operation == "+":
    print("Result:", num1 + num2)
elif operation == "-":
    print("Result:", num1 - num2)
elif operation == "*":
    print("Result:", num1 * num2)
elif operation == "/":
    if num2 != 0:
        print("Result:", num1 / num2)
    else:
        print("Error: Division by zero is not allowed.")
else:
    print("Invalid operation.")   

  # Simple Age Checker
  question5. py for Simple age checker
age = int(input("Enter your age: "))

if age < 18:
    print("You are a minor.")
elif 18 <= age <= 65:
    print("You are an adult.")
else:
    print("You are a senior.")

   # Password Validator
     question6. py for Password validator
password = input("Enter the password: ")

if password == "python123":
    print("Access granted.")
else:
    print("Access denied.")

   # Triangle Type Checker
    question7. py for Triangle type  checker
side1 = float(input("Enter the first side of the triangle: "))
side2 = float(input("Enter the second side of the triangle: "))
side3 = float(input("Enter the third side of the triangle: "))

if side1 == side2 == side3:
    print("The triangle is Equilateral.")
elif side1 == side2 or side2 == side3 or side1 == side3:
    print("The triangle is Isosceles.")
else:
    print("The triangle is Scalene.")

   # Day of the Week Checker
   question8. py for Day of the week  checker
day = int(input("Enter a number (1-7): "))

if day == 1:
    print("Monday")
elif day == 2:
    print("Tuesday")
elif day == 3:
    print("Wednesday")
elif day == 4:
    print("Thursday")
elif day == 5:
    print("Friday")
elif day == 6:
    print("Saturday")
elif day == 7:
    print("Sunday")
else:
    print("Invalid input.")
