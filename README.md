import math  # Import math module for sqrt function

result = 0

def add():
    x = int(input("Enter the first number: "))
    y = int(input("Enter the second number: "))
    result = x + y
    return result

def sub():
    x = int(input("Enter the first number: "))
    y = int(input("Enter the second number: "))
    result = x - y
    return result

def mul():
    x = int(input("Enter the first number: "))
    y = int(input("Enter the second number: "))
    result = x * y
    return result

def div():
    x = int(input("Enter the first number: "))
    y = int(input("Enter the second number: "))
    result = x / y
    return result

def sqrt():
    x = int(input("Enter the number: "))
    result = math.sqrt(x)
    return result

def power():
    x = int(input("Enter the base number: "))
    y = int(input("Enter the power: "))
    result = x ** y
    return result

while True:
    print("Welcome! Please select an option:")
    print("1. Addition")
    print("2. Subtraction")
    print("3. Multiplication")
    print("4. Division")
    print("5. Square Root")
    print("6. Power of a Number")
    print("7. Exit")

    choice = int(input("Enter your choice: "))
    if choice == 1:
        result = add()
        print(f"The answer is {result}")
    elif choice == 2:
        result = sub()
        print(f"The answer is {result}")
    elif choice == 3:
        result = mul()
        print(f"The answer is {result}")
    elif choice == 4:
        result = div()
        print(f"The answer is {result}")
    elif choice == 5:
        result = sqrt()
        print(f"The square root is {result}")
    elif choice == 6:
        result = power()
        print(f"The result is {result}")
    elif choice == 7:
        exit()
    else:
        print("Enter a valid option.")
