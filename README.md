# big-data-amazon-vine

![Amazon Vine](https://sm-us.nos-eastchina1.126.net/assets/news/content/20200208/d1519130ca25cff0724bed3c9b40b195.0x1920x1080.png)

A 'big data' ETL of Amazon review datasets provided at [Amazon review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt).

Two Amazon review datasets (Sports and Pets) were selected and read in to Google Colab notebooks using Spark.

The datasets were then broken down further into DataFrames for review_id_table, products, customers, and vine_table per the schema.sql file that can be found in the Resource folder of this repository.

The dataframes were then loaded into an RDS instance.
