# DataWarehouse for Electronic Retail Company

In this project I designed and developed Data Warehouse for the retail company which integrated 40 million of records in 45 mintues on MySQL Server. The source of data was from 4 different databases those were MS SQLServer, Postgres, Oracle 18c, and MySQL. I used talend tool for the ETL (Extract-Transform-Load). The performance increment was done using various techniques like Parallelization, Synchronization, configuring tHashInput, tHashOutput, and Hash Cache components and log removals which helped in achieving minimum time execution. Also, performed data profiling, identifying source to target mappings, used Type-2 SCD's (Slowly Changing Dimensions) for keeping the track of changing data in the warehouse, used Reject Codes for tracking the unknown entry in the warehouse. After integration, I developed interactive dashboards on tableau and Power BI which provided useful business insights such as Sales Profit, Annual Revenue, Customer Retention Rate, Sales to Inventory Ratio and various other Buisness KPI's.

## Techniques used in this project:

* Data Understanding - Data Profiling, Source-to-Target Mapping, Data Quality
* Data Design - Logical, Conceptual, Physical data Model development
* Multi-Dimensional Schema designing - Facts tables, Dimensions ( Role, Degenerative, Time, Event, Conforming)  
* ETL Jobs Creation 
* Master Job Creation 
* Testing 
* Performance Tuning 


## List of tools used in this project:

* Talend 
* Microsoft Excel 
* Tableau 
* Power BI 
