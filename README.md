# DAT275x
Principles of Machine Learning: Python Edition

# Challenge Overview

In 1998, the Adventure Works Cycles company collected a large volume of data about their existing customers, including demographic features and information about purchases they have made. The company is particularly interested in analyzing customer data to determine any apparent relationships between demographic features known about the customers and the likelihood of a customer purchasing a bike. Additionally, the analysis should endeavor to determine whether a customer's average monthly spend with the company can be predicted from known customer characteristics.

In this project, you must tackle three challenges:

Challenge 1: Explore the data and gain some insights into Adventure Works customer characteristics and purchasing behavior.

Challenge 2: Build a classification model to predict customer purchasing behavior.

Challenge 3: Build a regression model to predict customer purchasing behavior.

# About the Data

AdvWorksCusts.csv

Customer demographic data consisting of the following fields:

    CustomerID (integer): A unique customer identifier.
    Title (string): The customer's formal title (Mr, Mrs, Ms, Miss Dr, etc.)
    FirstName (string): The customer's first name.
    MiddleName (string): The customer's middle name.
    LastName (string): The customer's last name.
    Suffix (string): A suffix for the customer name (Jr, Sr, etc.)
    AddressLine1 (string): The first line of the customer's home address.
    AddressLine2 (string): The second line of the customer's home address.
    City (string): The city where the customer lives.
    StateProvince (string): The state or province where the customer lives.
    CountryRegion (string): The country or region where the customer lives.
    PostalCode (string): The postal code for the customer's address.
    PhoneNumber (string): The customer's telephone number.
    BirthDate (date): The customer's date of birth in the format YYYY-MM-DD.
    Education (string): The maximum level of education achieved by the customer:
        Partial High School
        High School
        Partial College
        Bachelors
        Graduate Degree
    Occupation (string): The type of job in which the customer is employed:
        Manual
        Skilled Manual
        Clerical
        Management
        Professional
    Gender (string): The customer's gender (for example, M for male, F for female, etc.)
    MaritalStatus (string): Whether the customer is married (M) or single (S).
    HomeOwnerFlag (integer): A Boolean flag indicating whether the customer owns their own home (1) or not (0).
    NumberCarsOwned (integer): The number of cars owned by the customer.
    NumberChildrenAtHome (integer): The number of children the customer has who live at home.
    TotalChildren (integer): The total number of children the customer has.
    YearlyIncome (decimal): The annual income of the customer.

AW_AveMonthSpend.csv

Sales data for existing customers, consisting of the following fields:

    CustomerID (integer): The unique identifier for the customer.
    AveMonthSpend (decimal): The amount of money the customer spends with Adventure Works Cycles on average each month.

AW_BikeBuyer.csv

Sales data for existing customers, consisting of the following fields:

    CustomerID (integer): The unique identifier for the customer.
    BikeBuyer (integer): A Boolean flag indicating whether a customer has previously purchased a bike (1) or not (0).

# Challenge 1: Data Exploration

To complete this challenge:

Download the Adventure Works data files - see previous unit.

Clean the data by replacing any missing values and removing duplicate rows. In this dataset, each customer is identified by a unique customer ID. The most recent version of a duplicated record should be retained.

Explore the data by calculating summary and descriptive statistics for the features in the dataset, calculating correlations between features, and creating data visualizations to determine apparent relationships in the data.

Based on your analysis of the customer data after removing all duplicate customer records, answer the questions below.
    
Enter the following summary statistics you calculated for the AveMonthSpend column.
