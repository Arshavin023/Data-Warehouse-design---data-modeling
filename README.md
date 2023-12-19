# Data Warehouse and data modeling

## `Scenario:`
In this project, a Data Engineer was tasked with designing data warehouse that would serve as single source of truth for analytics. Historical Data from different source systems were collected; accounting software, supplier's database, point of sales (POS) systems and CSV files.

## Existing data
![existing_data](https://github.com/Arshavin023/Data-Warehouse-design---data-modeling/assets/77532336/6cdc15f3-647a-4191-8d18-10a0eac2cc0a)


## `Steps Taken`
1. The Data Engineer first sought to understand the business use cases for the database e.g analytics, transactional processes, etc.
2. Next Logical database design where entities and attributes were identified, and an entity relationship diagram (ERD) was created using the pgAdmin
3. Tables were then normalized
4. Primary and Foreign Keys were defined to create relationships between tables and ensured referential integrity
5. Database objects were generated and ran with SQL scripts created with pgAdmin Tool from ERD diagram
6. Database tables were populated with existing data
7. Materialized views was created and exported as CSV files
8. Exported data was then imported into Db2 and  databases

![DHW ERD](https://github.com/Arshavin023/Data-Warehouse-design---data-modeling/assets/77532336/bbcdf2a8-200c-4122-a856-578964935008)
