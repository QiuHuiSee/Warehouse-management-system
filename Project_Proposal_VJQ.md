
# Project Proposal

## Warehouse Management System


Team Name                   : VJQ

Team Members                : Victor Lee Hao Chuan, Ng Jun Wei, See Qiu Hui

**Project Introduction**

  This project is to develop a warehouse database management system for a logistic manager to keep track of stock on hand. 
  
  The database consists of 2 databases which are interrelated. Among them are “Types of Products” and “Product information”. The database will be implemented on Django platform using Raspberry Pi.
	
  Besides, a graphical user interface will be built to ease the usage of this database. Android Studio will be used to create the interface and the programming language used in Android Studio is Java. 


**Use case diagram**

![image](https://user-images.githubusercontent.com/55492290/71544874-32714d80-29bf-11ea-9c65-809e3146021a.png)

**Object-Oriented Programming (OOP)**

  Object-oriented programming (OOP) is a type of computer programming in which programmers define the data type of a data structure and also the types of operations that can be applied to the data structure. The data structure becomes an object that includes both data and functions and programmers can create relationships between one object and another. 
	
  Object-oriented programming is implemented in this project through the creation of user interface on mobile phone where user can check on the stocks on hand at the warehouse through the development of user interface at Android Studio. This is due to the usage of class in the process of creating the mobile phone user interface. Class components are used as container components to handle state management and wrap child components.

**Database**

The project consists of 2 databases:

1. Types of Products
2. Product information 

**Database 1:**

Types of Products

| **ID** | **Description** | **Brand** | **Cost/Item (RM)** | **Manufacturer** |
| --- | --- | --- | --- | --- |
| 11885512 | Handbag | LV | 200 | YH Manufacturer |
| 11998795 | Sweater | Uniqlo | 175 | AZ Manufacturer |
| 11795562 | Phone | Samsung | 2999 | QH Manufacturer |

![image](https://user-images.githubusercontent.com/55492290/71544996-c55eb780-29c0-11ea-861d-e4e5e4fe63d6.png)


**Database 2:**

Product information

| **Time** | **Product1** | **Quantity1** | **Product2** | **Quantity2** | **Product3** | **Quantity3** |
| --- | --- | --- | --- | --- |
| 2019-12-06T03:14:26.058771Z | 1 | 210 | 2 | 2222 | 3 | 887 |

PS: Data above is for illustration purpose.
