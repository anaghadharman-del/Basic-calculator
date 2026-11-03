num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

print("Select an operation:")
print("1. Addition (+)")
print("2. Subtraction (-)")
print("3. Multiplication (*)")
print("4. Modulo (%)")
print("5. Exponentiation (**)")
print("6. Floor Division (//)")
print("7. Division (/)")

choice = input("Enter your choice (1-7): ")

if choice == "1":
    print("Result:", num1 + num2)

elif choice == "2":
    print("Result:", num1 - num2)

elif choice == "3":
    print("Result:", num1 * num2)

elif choice == "4":
    print("Result:", num1 % num2)

elif choice == "5":
    print("Result:", num1 ** num2)

elif choice == "6":
    print("Result:", num1 // num2)

elif choice == "7":
    print("Result:", num1 / num2)

else:
    print("Invalid choice")
