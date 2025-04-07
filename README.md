# Toys Company Sales Using Power BI
Developing an interactive dashboard for a toy company, "Maven Toys". Managers can use this dashboard to get comprehensive report about the sales of toys. The aim of this data analysis project is to create an interactive dashboard using Power BI for analyzing sales of a toy company. The project involves taking raw sales and inventory data, cleaning and transforming it into a suitable format, and then visualizing the insights through an interactive and user-friendly dashboard.

# Data Collection and Description:
We are given four files in CSV format described below:

Products:
1. Product_ID - ID of the Product
2. Product_Name - Name of the Product
3. Product_Category - Category of Product
4. Product_Cost - Product Cost (USD)
5. Product_Price - Retail Price (USD)

Sales:
1. Sale_ID - Sale ID for each transaction
2. Date - Date when the transaction occured
3. Store_ID - Unique ID given to toy store
4. Product_ID - ID of the Product
5. Units - Units of product sold


Stores:
1. Store_ID - Unique ID given to toy store
2. Store_Name - Store Name given of each toy store
3. Store_City - City where the store is located
4. Store_Location - Area where the store is located (Downtown,Commercial, Residential, Airport) Store_Open_Date - Store Opening Date


Inventory:
1. Store_ID - Unique ID given to toy store
2. Product_ID - ID of the Product
3. Stock_On_Hand - Units of products currently in the inventory


# Data Cleaning and Preparation:
1. Import files in Power BI.

2. Remove Duplicate Rows from all the files.

3. We connect the different files using respective Primary and Foreign Keys:
![alt text](https://github.com/mahmoudMoAbdelmoty/Toy-Sales-Company/blob/main/Datamodel.png?raw=true)

# Data Analysis

## Sales Performance
![alt text](https://github.com/mahmoudMoAbdelmoty/Toy-Sales-Company/blob/main/Sales Performance.png?raw=true)















