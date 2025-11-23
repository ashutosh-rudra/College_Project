 Simple Bank Account System (Python)
A basic Python program that simulates a bank account system using an Account class.
Users can:
•	Create an account
•	Credit money
•	Debit money
•	Check balance
This program uses object-oriented programming (OOP) concepts and user input for interaction.Features
•	Create an account with:
o	Account number
o	Opening balance
•	Credit amount to the account
•	Debit amount with insufficient balance check
•	View current balance
•	Menu-driven system for easy interaction
Code Overview
The program includes:Account Class
•	Stores balance and account number
•	credit(amount) – adds money
•	debit(amount) – subtracts money with balance validation
•	get_balance() – returns current balance
Menu-Driven Interface
Allows users to perform operations like:
1.	Credit amount
2.	Debit amount
3.	Check balance
4.	Exit
How to Run the Program
1.	Install Python 3.x
2.	Save the script as account.py
3.	Open terminal / command prompt
4.	Run:
python account.py
Example Usage
Enter your account number: 12345
Enter opening balance: 5000

Choose an option:
1. Credit amount
2. Debit amount
3. Check balance
4. Exit

Enter choice: 1
Enter amount to credit: 1000
Rs. 1000 was credited
Total balance = 6000
Requirements
•	Python 3.x
•	No external libraries needed
Future Improvements (optional)
•	Add PIN authentication
•	Store account details in a file or database
•	Add multiple accounts
•	Graphical User Interface (GUI)

