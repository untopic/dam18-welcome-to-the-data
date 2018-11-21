# Assignment 1: Redshift Alternatives

Task:

- Read about multiple REDSHIFT alternatives. 
- Spot their advantages and disadvantages. 
- Present your findings.

##Answer##

**Criteria:** 

-  SQL language (postgreSQL, SQL, other SQL variations...)
-  Managed vs licensed: Many existing data warehousing solutions require you to purchase a license, and then set up the warehouse on your own servers, whether they’re on the cloud or on-premise, physical servers.
-  Data processing: MPP most common. MPP (massively parallel processing) architecture means that your data and queries get distributed across all of your nodes for the most efficient storage and processing.
-  Scalability & availability: How quickly can increase and dcrease capacity in response to changing workloads
-  Price of connections and storage
-  Reliability
-  Entry cost
-  Security (patches and protocols)
-  Connection to other cloud services
-  JSON support

---

**Top players:** 

Amazon Redshift, Microsoft Azure, Google BigQuery, Snowflake

**Portfolio of products from a single vendor**

Amazon Redshift, Amazon Redshift Spectrum, 
Amazon Athena: You should consider Amazon Athena if you workload is more ad-hoc and you want to avoid the costs associated with an infrastructure like Redshift. It doesn’t require any installation or deployment on any cluster. The data is stored on Amazon S3, can be queried as needed using ANSI SQL, and you only will be charged for queries that you actually run. This might help you balance investments for storage and compute resources that might go underutilized in Redshift.

---

Benchmark Redshift, Snowflake, Azure, Presto, BiQguery: <https://fivetran.com/blog/warehouse-benchmark>

---

**Other options** 

HP Haven, IBM Pure, SAP, Pivotal, Teradata, Oracle Exadata...


