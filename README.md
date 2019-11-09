# Big Data Challenge: ETL & Analysis with AWS-RDS-PostgreSQL

Many of Amazon's shoppers depend on product reviews to make a purchase. [Amazon](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) makes these review datasets publicly available. However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite taxing on the average local computer. The first goal for this project was to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal was to use PySpark to perform a statistical analysis of selected data to determine whether reviews from Amazon's Vine program are trustworthy. Ultimately, I determined that Vine reviews may not offer a complete picture of their reliability simply due to the sheer quantity of non-vine reviews to Vine reviews.

Please visit the [Amazon Vine Help Page](https://www.amazon.com/gp/vine/help?ie=UTF8) for additional information regarding the program.

## Tools:

* AWS: RDS-PostgreSQL

* ZEPL Data Science Notebook Hub

* Apache Spark: PySpark

* Jupyter Notebook (To copy code snippets from ZEPL)

## Documentation & Navigation:

* big-data-challenge (Root)

  * README.md
  
  * Resources (Folder)
  
    * schema.sql ---> SQL Queries to build tables
    
    * vine_schema.sql ---> SQL Query to build vine table
    
  * level-1 (Folder)
  
    * big-data-challenge-level-1.ipynb ---> Code copied from ZEPL Notebook
    
    * big-data-challenge-level-1.pdf ---> Image of Output
    
  * level-2 (Folder)
  
    * big-data-challenge-level-2.ipynb ---> Code copied from ZEPL Notebook
    
    * big-data-challenge-level-2.pdf ---> Image of Output
