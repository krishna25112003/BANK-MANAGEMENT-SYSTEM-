Bank Management System 

This C++ program implements a simple Bank Management System. The system allows users to perform various operations related to managing customer accounts. Below is a brief overview of the program's features and usage:

Features:
Create new account: Allows the user to create one or more new bank accounts by providing necessary details such as name, last name, phone number, email, username, password, and initial transaction amount.

Update information: Enables the user to update information for an existing account by entering the username associated with that account. The user can modify details such as name, last name, phone number, email, username, password, and transaction amount.

Check account details: Allows the user to view details of an existing account by entering the username. This includes information such as name, last name, phone number, email, username, password, and current transaction amount.

Transactions: Supports deposit and withdrawal transactions for existing accounts. The user must input the username associated with the account and choose between depositing or withdrawing money.

Remove existing account: Provides options to delete either a specific account or all accounts. When deleting a specific account, the user needs to enter the username associated with that account.

View customers list: Displays a list of all customer accounts with their respective details.

Exit: Exits the program.

How to Use:
Compile and run the program in a C++ environment.

The initial screen displays the Bank Management System title, which fades in and out.

After the title animation, a menu with seven options is presented to the user.

The user can select an option by entering the corresponding number.

Depending on the selected option, the user may need to input additional details such as the number of accounts to create, the username for updating or checking details, the transaction type (deposit or withdraw), etc.

The program provides feedback on the performed operations, such as account creation, updating information, or deletion.

The system continues to run until the user chooses the "Exit" option.

Note:
The program uses the windows.h library for title animation and Sleep function, which may not be compatible with all operating systems.

The code structure includes a bank class to encapsulate data and operations related to the bank accounts.

Error handling for invalid inputs or edge cases is limited, and additional enhancements can be made to improve the robustness of the program.

The program utilizes the system("CLS") command for clearing the console, which might not work as expected on all platforms.

It is advisable to run the program in an environment that supports the features and libraries used in the code.

Feel free to explore, modify, and enhance the program based on specific requirements or preferences.
