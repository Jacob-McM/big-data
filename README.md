# Interacting with "Big Data" - Utilizing PySpark and AWS

This is a repo demonstrating the ETL process utilizing a "Big Data" dataset as provided by [Amazon](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt).

This ETL process was done across two Google Colab notebooks. Within these notebooks, PySpark was utilized to interact with our dataset and schema. AWS RDS service was utilized as the database host. the RDS service used was formatted as a PostgresSQL database. 

Analysis using PySpark was done after the dataset was loaded. The analysis can be found at the bottom of the [Instruments Reviews Notebook.](instrument_loading.ipynb).

In this repo you will find:

|Notebook|Description|
|--|--|
|[Instrument Loading Notebook](instrument_loading.ipynb)|This notebook contains the PySpark ETL for an Amazons S3 bucket of Instrument review data. The data is loaded using AWS RDS services.|
|[PC Parts Loading Notebook](PC_parts_loading.ipynb)| This notebook contains the PySpark ETL for an Amazon provided S3 bucket of PC Part review data. The data is loaded into a PostgreSQL type database using AWS RDS services.|

Both notebooks were created, and imported into GitHub, using Google Colab.

---

### Acknowledgements/Resources

##### Amazon customer Reviews Dataset. (n.d.). Retrieved Nov 29, 2022, from: https://s3.amazonaws.com/amazon-reviews-pds/readme.html

##### © 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.

##### Helper/Starter code provided by my instructor, Dom. L.
