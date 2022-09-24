# AWS Glue 
AWS Glue is fully managed ETL (Extract, Transform and load) service provided by aws thatmakes it simple and cost-effective to categorize your data.Clean it, enrich it and move to reliably between various data stores.

## Steps
- Create crawlers : A crawler connects to a data store, progresses through a prioritized list of classifiers to determine the schema for your data, and then creates metadata tables in your data catalog.
- Run crawlers
- AWS Glue Studio : AWS Glue Studio is an easy-to-use graphical interface for creating, running, and monitoring ETL jobs.

## AWS Glue Studio Screenshots

- Source data schema: Here we used AWS glue data catalog as source data, "mlb_id" field is of type string.

![Logo](https://github.com/Kajal-ghadage2000/AWS-Training/blob/main/AWS-Glue/source%20data%20schema.png)


- Transform data : Change "mlb_id" field data type as "smallint".

![Logo](https://github.com/Kajal-ghadage2000/AWS-Training/blob/main/AWS-Glue/transform%20data.png)


- Target data schema : Data transformation is successful and now "mlb_id" is of type smallint.

![Logo](https://github.com/Kajal-ghadage2000/AWS-Training/blob/main/AWS-Glue/target%20data%20schema.png)



## Reference 
- [AWS Glue](https://catalog.us-east-1.prod.workshops.aws/workshops/976050cc-0606-4b23-b49f-ca7b8ac4b153/en-US/600/610-glue-data-validation-etl)
