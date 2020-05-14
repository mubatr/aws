# This project contains 2 files

1. Input file - This is a CSV file containing data that will be transformed using Glue. This needs to be placed in the S3 bucket.
2. Spark Script - This script needs to be added while defining Glue Job in AWS. This script will read the data from Glue DB, aggregate the data and generate a new file in write folder in S3 bucket.
