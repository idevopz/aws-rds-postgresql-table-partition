***[aws-rds-postgreqsl-table-partition](https://github.com/idevopz/aws-rds-postgreqsl-table-partition)***

AWS PostgreSQL RDS Table Partition

Here is a sample script for partitioning. You can use this as a reference and perform the same operation on your table.

***[Validate each partition](https://github.com/idevopz/aws-rds-postgreqsl-table-partition):***

select * from datablogspaycheck_202303 order by 2 desc

select * from datablogspaycheck_20230304 order by 2 desc

select * from datablogspaycheck_202311 order by 2 desc
