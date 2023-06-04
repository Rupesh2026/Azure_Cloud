**Azure_Data_Factory_Covid19_Project** -- This project aims to retrieve COVID-19
Data from the ECDC (European Centre for Disease Prevention and Control) website, load it into Azure Blob Storage, and perform various data transformation tasks using Azure Data Factory (ADF). 
The transformed data will then be loaded into Azure Data Lake Gen2, and further processed to populate a SQL database for Power BI and machine learning model development. 
Steps:
**Data Extraction:** The first step involves extracting COVID-19 data from the ECDC website. We will use web scraping techniques to retrieve the required data in a structured format.
**Azure Blob Storage:** The extracted data will be stored in Azure Blob Storage, which provides a reliable and scalable storage solution. We will set up a storage account and create containers to hold the data. 
**Data Loading:** Once the data is stored in Azure Blob Storage, we will use Azure Data Factory to create pipelines for loading the data into Azure Data Lake Gen2. Data Factory offers a managed and scalable service for data integration and orchestration. 
**Data Transformation:** Using Azure Data Factory, we will employ data flow tasks to transform the COVID-19 data as per our requirements. Data flows provide a visual interface for building complex data transformation logic without writing code. 
**Azure Data Lake Gen2:** The transformed data will be stored in Azure Data Lake Gen2, which is a highly scalable and secure data storage service. We will create a data lake storage account and organize the data into appropriate folders and files.
**Linked Services and Data Sets:** To establish connectivity and define the data sources, we will create linked services and data sets in Azure Data Factory. Linked services provide the necessary information to connect to external data sources, while data sets define the structure and schema of the data.
**SQL Database:** We will create a SQL database in Azure to serve as the destination for our transformed data. This database will be used for Power BI visualization and machine learning model development.
**Data Loading into SQL Database:** Finally, we will configure Azure Data Factory to load the transformed data from Azure Data Lake Gen2 into the SQL database. This step enables seamless integration with Power BI and other analytics tools for data analysis and reporting.
