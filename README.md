# Bank-Account

The Bank Account System is a Java program that demonstrates the usage of checking and savings accounts. It creates instances of the CheckingAccount and SavingsAccount classes and performs operations related to these accounts.

How to Use
Open the Java file named MainClass.java in your preferred Integrated Development Environment (IDE) or text editor.

Import the necessary classes for the checking and savings accounts:

import week12.CheckingAccount;
import week12.SavingsAccount;
The MainClass extends the BankAccount class, which is assumed to exist elsewhere in the codebase.

Within the main method of the MainClass, instances of CheckingAccount and SavingsAccount are created:

CheckingAccount ck = new CheckingAccount();
SavingsAccount sa = new SavingsAccount();
Various methods are called on the CheckingAccount and SavingsAccount instances to retrieve account information:

ck.getAccountHolderName();
ck.getAccountBalance();
ck.getAccountNumber();

sa.getAccountHolderName();
sa.getAccountBalance();
sa.getAccountNumber();
The program then outputs the account details using System.out.println():

System.out.println(ck);
System.out.println(sa);
The program terminates after printing the account details.

Account Classes
CheckingAccount
The CheckingAccount class represents a checking account and provides methods to manage and retrieve account information.

SavingsAccount
The SavingsAccount class represents a savings account and provides methods to manage and retrieve account information.

Contributing
Contributions to the Bank Account Management System are currently not being accepted as this is a simplified code snippet provided for demonstration purposes.

License
The Bank Account System is not subject to any license as it is a code snippet provided for reference and educational purposes.

Author
This code snippet is provided as an example. Feel free to adapt and modify it according to your needs.




