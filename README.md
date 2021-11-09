# **Movies-ETL**

### **Purpose**
The main objective of the ETL process of the movies data was achieved and a fully-functional sql data was created for the hackathon.
However, an automated process is now required to keep this database updated on a daily basis, therefor the purpose of this project is to develop an all-inclusive ETL function for the hackathon.

#

## **Results**
3 Jupyter nootebooks were created to build the ETL function for the 3 data sources. 

Finally, in a 4th notebook a python function was developed to:
* Extract 1 JSON file and 2 csvs sources.
* Clean all the databases to fulfill the hackathon contest.
* Merge the final data frames to have only 1 Database with movies info and ratings-
* Export both the raw ratings data and the created Database.