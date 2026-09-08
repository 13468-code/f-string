# Prompt the user to enter two numbers
# float() allows for both whole numbers and decimals
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Conduct the calculations
addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2
division = num1 / num2
integer_division = num1 // num2
remainder = **num1** % num2
exponentiation = num1 ** num2

# Display the results back to the user using f-strings
print("\n--- Results ---")
print(f"Addition: {num1} + {num2} = {num1 + num2}")
print(f"Subtraction: {num1} - {num2} = {num1 - num2}")
print(f"Multiplication: {num1} * {num2} = {num1 * num2}")
print(f"Division: {num1} / {num2} = {num1 / num2}")
print(f"Integer Division: {num1} // {num2} = {num1 // num2}")
print(f"Remainder: {num1} % {num2} = {num1 % num2}")
print(f"Exponentiation: {num1} ** {num2} = ( {num1 ** num2} )
