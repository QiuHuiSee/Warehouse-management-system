##

##

# Project Proposal



## Warehouse Management System





Team Name                   : VJQ

Team Members                : Victor Lee Hao Chuan, Ng Jun Wei, See Qiu Hui

**Project Introduction**

    This project is to develop a warehouse database management system for a logistic manager to keep track of stock on hand.

    The database consists of 3 databases which are interrelated. Among them are &quot;Number of Stock On Hand&quot;, &quot;Types of Products&quot; and &quot;Information of Warehouses&quot;. The database will be implemented on MySQL platform using Raspberry Pi.

    Besides, a graphical user interface will be built to ease the usage of this database. React Native library in JavaScript will be used to create the interface.

**Use case diagram**

 ![use case](https://drive.google.com/drive/folders/16y1092I3BcMLaOp6FH5LZ4Pf69BZBu3w)

**Object-Oriented Programming (OOP)**

    Object-oriented programming (OOP) is a type of computer programming in which programmers define the data type of a data structure and also the types of operations that can be applied to the data structure. The data structure becomes an object that includes both data and functions and programmers can create relationships between one object and another.

    Object-oriented programming is implemented in this project through the creation of user interface on mobile phone where user can check on the stocks on hand at the warehouse through the usage of React Native in JavaScript. This is due to the usage of class in the process of creating the mobile phone user interface. Class components are used as container components to handle state management and wrap child components.

**Database**

The project consists of 3 databases:

1. Number of Stock On Hand
2. Types of Products
3. Information of Warehouses

**Database 1:**

Number of Stock On Hand

| **Product ID** | **Total Quantity** | **Distribution of Product** | **Price/Unit (RM)** | **Profit/Unit (RM)** |
| --- | --- | --- | --- | --- |
| 11885512 | 100 | Warehouse 001 | 40 | 900 | 700 |
| Warehouse 002 | 50 |
| Warehouse 003 | 10 |

 ![database](https://drive.google.com/drive/folders/16y1092I3BcMLaOp6FH5LZ4Pf69BZBu3w)



**Database 2:**

Types of Products

| **ID** | **Description** | **Brand** | **Cost/Item (RM)** | **Manufacturer** |
| --- | --- | --- | --- | --- |
| 11885512 | Handbag | LV | 200 | ABC Manufacturer |



**Database 3:**

Information of Warehouses

| **ID** | **City** | **Country** | **Person In Charge** | **Contact Number** |
| --- | --- | --- | --- | --- |
| Warehouse 001 | Johor Bahru | Malaysia | Jack Ma | +6016-4488567 |
| Warehouse 002 | New York | US | Bob Swan | +156200-1503 |
| Warehouse 003 | Bangkok | Thailand | Chalermchai Kositpipat | +6602-2134567 |

PS: Data above is for illustration purpose.
