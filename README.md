# Crowdfunding_ETL
## Collaboration between Katie Beale, Megan Palma, and Jared Willson

### Summary
This repository contains code to perform ETL (Extract, Transform, and Load) functions against data contained in a "crowdfunding.xlsx" spreadsheet. The spreadsheet is first loaded into Pandas, datatypes examined for accuracy, split into multiple dataframes that will allow for a fully normalized structure within a PostgreSQL databse. The data for the four normalized tables are split into four CSV files for import into a database. They are: campaign.csv, category.csv, subcategory.csv, and contacts.csv all within the Resources subdirectory. The campaign.csv file contains information on each individual campaign. The contacts.csv file contains information name and email information on the owner of each campaign. The category.csv and subcategory.csv files contain respectively information on each valid category and subcategory that might be used in the campaigns. Using QuickDataabaseDiagrams, a file called crowdfunding_db_schema.sql was created in order to generate an appropriate schema within PostgreSQL. It is stored in the Resources folder. 

### Instructions for use. 


### Additional Resources
Assitance was received from Xpert Learning for the eval(JSON) section of the code in order to convert a text string into a dictionary within Pandas. https://www.quickdatabasediagrams.com was used to build out the schema for a MySQL database using the four CSV files exported from the Pandas code in the Jupyter notebook. 