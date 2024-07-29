# Project 2 - Crowdfunding_ETL 

## Instructions
### The instructions for this mini project are divided into the following subsections:

- Create the Category and Subcategory DataFrames
- Create the Campaign DataFrame
- Create the Contacts DataFrame
- Create the Crowdfunding Database

Raw Data Files (.xlsx) stored in "Crowdfunding_ETL/Resources"

### Code Reference
#### Create the Dataframes (Category, Subcategory, Campaign, Contacts)

- <u>ETL_Mini_Project_Starter_Code.ipynb</u>
  - Option 1 (Python dictionary methods) utilized
  - Finalized dataframes stored in "Crowdfunding_ETL/Resources/crowdfunding_db"
    - contacts.csv
    - category.csv
    - subcategory.csv
    - campaign.csv

#### Create the Crowdfunding Database

- <u>crowdfunding_db_schema.sql</u>
  - Create crowdfunding_db
    - <img src="Images\crowdfunding_db_create.png" width="1000"/>
  - Create a table schema for each csv file
    - <img src="Images\Table_Schema_all_tables.png" width="1000"/>
  
  - Import of each data file into corresponding SQL table and querying of each table for validation
    - 'contact' table
      - <img src="Images\Table_contacts_import_query.png" width="1000"/> 
    - 'category' table
      - <img src="Images\Table_category_import_query.png" width="1000"/> 
    - 'subcategory' table
      - <img src="Images\Table_subcategory_import_query.png" width="1000"/>
    - 'campaign' table
      - <img src="Images\Table_campaign_import_query.png" width="1000"/> 
  

## Code Source
- Learning Assistant
- GitHub location: https://github.com/jeffjunohkim/Crowdfunding_ETL.git




