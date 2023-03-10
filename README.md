# Crowdfunding-ETL
The Crowdfunding ETL Project by Woyram and Britta involved Data Extraction, Transformation and Cleaning with Python on crowdfunding dataset https://github.com/WoyramA/Crowdfunding-ETL/blob/main/Crowdfunding.ipynb. The data cleaned was then exported as the following tables in csv form:

Campaing: 
https://github.com/WoyramA/Crowdfunding-ETL/blob/main/campaign.csv
Category: 
https://github.com/WoyramA/Crowdfunding-ETL/blob/main/category_file.csv
Subcategory: 
https://github.com/WoyramA/Crowdfunding-ETL/blob/main/subcategory_file.csv
Contacts:
https://github.com/WoyramA/Crowdfunding-ETL/blob/main/contacts.csv

An ERD was created for the four tables for the campaing, contacts, category and subcategory. The Table Schema was then ready to be used to process the data with SQL. 


## Overview
Following, the successful processing extrction, transformation, cleaning and loading of the crowdfunding data, Independent funding then provided a new dataset (backers_info) about the campaign backers which was added to the initial dataset by the Britta-Woyram team. The new dataset was extracted, transformed and cleaned with Python, into the backers table as backers.csv. The cleaned backers data was then used to create a new ERD and Schema, used to generate queries to create two tables to show the remaining goal amount from the campaign. 

## Results
In Crowdfunding-ETL project, four deliverables were expected from the Britta-Woyram team. Results of the project are delivered below:

### Deliverable 1 and 2 
Deliverable 1 as code that captures the extraction and transformation part of the backers_info.csv data while the Deliverable 2 portion contains code used to clean and save the data into bakers.csv  
https://github.com/WoyramA/Crowdfunding-ETL/blob/main/Extract-Transform_starter_code_final.ipynb 

### Deliverable 3
Deliverable 3 being an ERD Diagram, a Schema and backers file.
#### ERD 
A relationship diagram between the four tables for the campaign, category, subcategory, contacts and the backers table was created.
https://github.com/WoyramA/Crowdfunding-ETL/blob/main/crowdfunding_db_relationships.png.png

### Schema
A schema with code for all five tables for campaign, category, subcategory, contacts and the backers was generated for loading tables SQL
https://github.com/WoyramA/Crowdfunding-ETL/blob/main/updatedcrowdfunding_db_schema.sql.sql

### Backers file
https://github.com/WoyramA/Crowdfunding-ETL/blob/main/backers.csv
Backers Table: 
![image](https://user-images.githubusercontent.com/114967995/216800882-392ec88d-b5d7-4e96-a95d-2fc95244037f.png)

### Deliverable 4
The SQL_Analysis_Schema https://github.com/WoyramA/Crowdfunding-ETL/blob/main/crowdfunding_SQL_Analysis.sql.sql was used to generate two tables as follows:

Table 1: 
The email_contacts_remaining_goal_amount showing the firstnames, lastnames, email address and the remaining goal amount (as "Remaining Goal Amount") in descending order for each live campaign. https://github.com/WoyramA/Crowdfunding-ETL/blob/main/email_contacts_remaining_goal_amount.csv

Tabel 1

![image](https://user-images.githubusercontent.com/114967995/216802260-43f53145-3360-44ab-82c0-615f19d4c71c.png)


Table 2 
The email_backers_remaining_goal_amount containing the email addresses of the backers in descending order, the first and the last name, the cf_id, company name, description, the end date of the campaign, and the remaining amount of the campaign goal as ("Left of Goal").
https://github.com/WoyramA/Crowdfunding-ETL/blob/main/email_backers_remaining_goal_amount.csv


## Summary
The Crowdfunding-ETL task resulted in successfully extracting, transforming, cleaning and loading data using ERD and Schema code. The tables capturing the details of the contacts of the live campaign to show the 'Remaining goal amount' and 'Left of goal' were obtained. 

