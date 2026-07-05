# amir
im amir
def calculator():
    print("Simple Calculator")
    print("1. Add")
    print("2. Subtract")
    print("3. Multiply")
    prin("4. Divide")

    choice = input("Choose (1-4): ")

    num1 = float(input("First number: "))
    num2 = float(input("Second number: "))

    if choice == "1":
        print("Result:", num1 + num2)
    elif choice == "2":
        print("Result:", num1 - num2)
    elif choice == "3":
        print("Result:", num1 * num2)
    elif choice == "4":
        if num2 != 0:
            print("Result:", num1 / num2)
        else:
            print("Cannot divide by zero.")
    ele:
        print("Invalid choice.")

calculator(
List the advantages and disadvantages.
