# ATM Simulator
account_balance = 5000
def display_menu():
    print("ATM Simulator")
    print("1. Check Balance")
    print("2. Withdraw Cash")
    print("3. Deposit Cash")
    print("4. Quit")
def check_balance():
    print("Your current balance is: $", account_balance)
def withdraw_cash():
    amount = float(input("Enter the amount to withdraw: $"))
    global account_balance

    if amount > account_balance:
        print("Insufficient balance.")
    else:
        account_balance -= amount
        print("Amount withdrawn: $", amount)
        print("Remaining balance: $", account_balance)
def deposit_cash():
    amount = float(input("Enter the amount to deposit: $"))
    global account_balance

    account_balance += amount
    print("Amount deposited: $", amount)
    print("Updated balance: $", account_balance)

#Driver program
while True:
    display_menu()

    choice = input("Enter your choice (1-4): ")

    if choice == '1':
        check_balance()
    elif choice == '2':
        withdraw_cash()
    elif choice == '3':
        deposit_cash()
    elif choice == '4':
        print("Thank you for using the ATM. Goodbye!")
        break
    else:
        print("Invalid choice. Please try again.")
