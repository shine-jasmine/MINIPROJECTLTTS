# Requirements
## Introduction
*Customer Billing System Project is a simple console application designed to demonstrate the practical use of C programming language and its features as wells as to generate an application which can be used in any departmental store, shops, cafes etc. for billing to the customer.

*You can use this application to keep the records such as name, address, mobile number, paid amount, due amount, payment date etc. of your regular costumer. Moreover, if you have a new customer, you can add and edit the account at any time.

## Features

* It can hold any number of accounts and account can be added to the program at any time.
* The programming of simple calculations such as calculation of due amount, balance etc. have been embed in the code of project.
* The Customer Billing System project in C gives you the facility of searching the account by two ways, either by name of the customer or by the number of customer.
* The due amount to be paid is shown as negative balance.
* If you have nothing to do with the program, you can directly exit from the main menu.

### Services Offered to the Customers
* A customer can create an account for his own and give his details such as address to be stored.
* This helps the store to provide home delivery to the customer.
* The billing history of the customer is maintained.
* The customer can maintain some amount as balance to pay cash less as and when required in any brach of that departmental store.
* The customer can edit the information in his account as and when required.

### User Defined Function Used:
* Although graphics has not been used in this project, the application of user defined functions and structures have been effectively used here. The major user defined functions used in this C project are:

void input()
void writefile()
void search()
void output()
* The function void input() is used to add the new customer account i.e. with the help of this functions the parameters such as name, address, phone number, amount paid etc. are asked and entered. Another function void writefile() has been utilized to create a file on hard disc of computer for storing the information and data of a customer.

* The function void search() has been used to look for previously stored accounts either by name or by number of the customer. The fourth and the last user defined function used in this Customer Billing System Project in C is void output() which has been defined to show the result as console output.

* In Customer Billing System, structure has very beautifully used to group the data type in single unit. The date variables (day, month and year) have been grouped in the structures named date where as other variables such as name, number, street, paid amount etc. are grouped under another structure named account.

### Used For:

* To add account
* To search account
* To exit
As per your need, enter 1, 2,or 3 and follow the instructions provided by the application itself.

### Integration
The Customer Billing System interacts with :
  * Banking applications
  * Firewalls
  * Authentication gateways
  
![restaurant-billing-application-26-638](https://user-images.githubusercontent.com/80335764/114905342-7a2b1b00-9e36-11eb-8f9f-445595ab625e.jpg)


## SWOT Analysis
![Screenshot (6)](https://user-images.githubusercontent.com/80335764/114905260-641d5a80-9e36-11eb-954a-6db735ba3766.png)


# High and Low Level Requirements

## High Level Requirements

| ID  | Description  | Category  | Status  |
| --- | ------------ | --------- | ------- |
| HR01| New customer can create account | Techinal | TBI |
| HR02| Customer can mantain a Balance | Technical | TBI |
| HR03| Customer information can be displayed| Technical | TBI|
| HR03| Customer can pay the bill from e-wallet | Techinal | TBI|
| HR04| Customer can maintain money in account's wallet| technical|TBI|
| HR05| The last transaction amount of the custmoer in the store have to be maintained| Technical | TBI|
| HR06| Customer can opt for home delivery | Technical | FUTURE|
| HR07| The data should not be lost during failure | Scenario | FUTURE|
| HR08| The information of the customer sould not be leaked| Scenario | FUTURE|
| HR09| All the tracsanctions fron the creation of the account have to be maintained | Technical | FUTURE|

## Low Level Requirements

|ID | Description | HRID | Status|
|---|-------------|------|-------|
|LR01| For Each new account a new array cell of structure type have to be created| HR01 | TBI|
|LR02| Balance can be mantanied by creating a structure array each cell holding information of the user and their balance| HR02| TBI|
|LR03| Customer information can be displayed by printing the structure array| HR03| TBI|
|LR04| When paying bill the balance attribute is modified and updated| HR04|TBI|
|LR05| The home delivery option cane be implemented by taking the address of the customer|HR06|FUTURE|
|LR06| The data can be protected by using file to store all the data|HR07|FUTURE|
|LR07| The authentication mechanisms have to be implementd to prevent data leakage|HR08|FUTURE|
|LR08| All the transactionc can be maintained in a file dedicated to that customer|HR08|FUTURE|
