# gz-dbt-repository
Gz is a fictional e-commerce store. This dbt project transforms raw data from their website into a sales model ready for analytics. 
<img width="957" alt="Screenshot 2024-01-26 at 11 14 31" src="https://github.com/larixgomex/gz-dbt-repository/assets/126865773/dc180169-d9d7-49ff-958f-45a44de6387b">  
**Data Source:** tables located in BigQuery.
* raw_gz_sales 
* raw_gz_product 
* raw_gz_ship
### What is this repo?
A dbt project demonstrating sources, staging models, intermediate models, and marts. It provides an overview of dbt core concepts and its final consumer is the finance team in the company.

### What's in this repo?
- [A detailed schema of the source tables](https://github.com/larixgomex/gz-dbt-repository/blob/main/models/schema.yml)
- [Schema of the models created](https://github.com/larixgomex/gz-dbt-repository/blob/main/models/intermediate/schema.yml)  
⟶The raw data consists of orders, costs, and payments.  

### What is the purpose of this project?
Creating a well-structured data pipeline using dbt that adheres to the following principles:
- Data Accuracy and Protection: The pipeline should be designed to prevent the insertion of incorrect or erroneous data into the production environment, ensuring data accuracy and integrity.  

- Error Identification and Handling: The pipeline should have mechanisms in place to break down complexity, making it easy to identify and handle any new errors that may arise without disrupting access to data.

- Organized and Accessible Structure: The data should be organized and stored in a separate dataset to prevent any potential misunderstandings regarding its structure or usage within the finance team.

- Comprehensive Documentation: Provide detailed and comprehensive documentation of the table, including its columns, and lineage to understand where the data are coming from to enhance understanding and usage.

  
