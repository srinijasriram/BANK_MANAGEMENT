# BANK_MANAGEMENT
This project is done using python language and database with sqlite3 library.


There are two tables , they are user and bank.
User table attributes -- name , password to account , date of birth , date of account creation, address, mobile number, balance (initial deposit amount).
Bank table attributes – account number, username, user password
The user and bank table must linked with the primary key attribute that is password is a referential key to user password attribute in bank table(with help of foreign key).
The operations perform on tables are:
	1.Create A New Account
  2.View List Of User accounts
  3.View Account Balance
  4.Deposit Amount
  5.Withdrawal amount
  6.Delete An Account
  7.Update An Account
  8.Display Bank Accounts

Based on operations as shown above the user perform the their tasks .

In update operation there are some sub-operations

Here, the aim of project not only the opeations done properly, but main thing is to provide security to user and bank data. This security is done in this project by means of passwords.
which are unique in case of users and in case of bank there is only one password to access the bank records. Because the bank records must be accessed by bank authorized employees.
Actually in this project i gave the password of bank statically, bacause it is user and bank interface. In case of only bank interface it is good give dynamically changing bank password.
in this project case the user should not get the changing bank password operation!!
