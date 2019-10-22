##

##

# Project Proposal



# Warehouse Management System









Team Name                        : VJQ

Team Members                : Victor Lee Hao Chuan

                                           Ng Jun Wei

                                            See Qiu Hui

**Project Introduction**

**       ** This project is to develop a warehouse database management system for a logistic manager to keep track of stock on hand.

        The database consists of 3 databases which are interrelated. Among them are &quot;Number of Stock On Hand&quot;, &quot;Types of Products&quot; and &quot;Information of Warehouses&quot;. The database will be implemented on MySQL platform using Raspberry Pi.

        Besides, a graphical user interface will be built to ease the usage of this database. React Native library in JavaScript will be used to create the interface.

**Use case diagram**

 ![](data:image/*;base64,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)

 ![](data:image/*;base64,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)

 ![](data:image/*;base64,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)





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