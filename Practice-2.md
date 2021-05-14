# Practice Test 2

### **Question**  **1**

Domain :Describe how to work with relational data on Azure

Which of the following is not true about a relational table?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Values in the table are atomic**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**All the rows in the table are unique**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**The sequence of rows matters in the table.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Each column needs to have a unique name.**

**Explanation:**

**Correct Answer: C**

The sequence of rows does not matter in a relational table.The rows can be retrieved in any order and sequence. Adding data to a relational table does not affect the other existing queries.

- **Option A is incorrect.**  A relational table needs to have atomic values. Having atomic values is the condition for the table, being in first normal form. Atomic values are the values that can&#39;t be divided. It means that columns in the relational table are not repeating groups. For example, in below given table, the coloUr column is not having atomic values. The value &quot; Red, Black&quot; for Item \_Id 101  is not atomic and can be divided into two values Red and black.

| **Item\_Id** | **ColoUr** | **Price** |
| --- | --- | --- |
| 101 | Red, Black | 100 |
| 102 | White | 50 |
| 103 | Green | 70 |

- **Option B is incorrect. ** Unique rows is the essential characteristic of a relational table. No two rows in the table can&#39;t be the same. They need to vary for values of one or more columns that is ensured with the primary key in a relational table.
- **Option C is CORRECT.**  The sequence of rows does not matter in a relational table. The rows can be retrieved in any order and sequence. Adding data to a relational table does not affect the other existing queries.
- **Option D is incorrect.  ** In a relational table, each column needs to have a unique name as columns are referred in the table by their name, not their position as the position of the columns in the relational table is insignificant. Moreover, the names of the columns must be different in a table not in the database which means that two different tables in a database can have the same name for a column.

**Reference:**

To know more about the Relational Tables, refer to the documentation below:

- [https://www.cs.wcupa.edu/~zjiang/RDB\_table.htm](https://www.cs.wcupa.edu/~zjiang/RDB_table.htm)

### **Question**  **2**

Domain :Describe how to work with relational data on Azure

Which of the following statement is not true about Views in Relational database?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**A view is a virtual table that has the content defined by a query.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**A view can be created from multiple tables, a single table or even another view**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**One of the most important use of view is to simplify, focus and customize the users&#39; perception of the database. **

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**A view is a special lookup table that the database search engine can utilize to speed up the data retrieval.**

**Explanation:**

**Correct Answer: D**

A view is a virtual table that has the content defined by a query.Like a relational table, a view has a set of named rows and columns of data. A view can be created from multiple tables, a single table or even another view. Views are generally used to simplify, focus and customize the users&#39; perception of the database. Views can help improve query response time.

- **Option A is incorrect ** as a view is a virtual table that has the content defined by a query.
- **Option B is incorrect ** as a view can be created from multiple tables, a single table or even another view.
- **Option C is incorrect**  as Views are virtual tables that are generally used to simplify, focus and customize the users&#39; perception of the database.
- **Option D is CORRECT. ** as it is the index, not view, that is a  **special lookup table**  that the database search engine can utilize to speed up the data retrieval.

**Reference:**

To know more about Views in Relational Databases, refer to the documentation below from Azure:

- [https://docs.microsoft.com/en-us/sql/relational-databases/views/views?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/views/views?view=sql-server-ver15)

### **Question**  **3**

Domain :Describe how to work with relational data on Azure

Statement 1: Azure SQL Database handles updating and patching the SQL Server software automatically without user involvement.

Statement 2: Azure SQL Database offers scalability that ensures that you can enhance the number of resources available to store.

Statement 3: Azure SQL Database has an important feature of point-in-time restore, through which the database can be recoveredto the state of any specific point in the past.

Which of the above-given statements are true about Azure SQL database?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Only statement 1 and 3**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Only Statement 2 and 3**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Only statement 1 and 2**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**All statements 1, 2 and 3**

**Explanation:**

**Correct Answer: D     **

Azure SQL Database is a completely managed PaaS (Platform-as-a-Service) database engine that supports and handles the important database management functions like upgrading, patching, monitoring and backups automatically without the user&#39;s involvement.High availability, Scalability and Point-in-time restore are other important features of Azure SQL database.

- **Option A is incorrect**  as not only statement 1 and 3 but also statement 2 is true about Azure SQL database.  Scalability is also an important feature of Azure SQL database.
- **Option B is incorrect ** as not only statement 2 and 3 but also statement 1 is true about Azure SQL database.  Azure SQL database handles updating and patching the SQL Server software automatically.
- **Option C is incorrect**  as not only statement 1 and 2 but also statement 3 is true about Azure SQL database.  Azure SQL database allows recovering the databaseto the state of any specific point in the past through its point-in-time restore feature.
- **Option D is CORRECT ** as manually updating and patching, high scalability and point-in-time restore are important features of Azure SQL database.

**Reference:**

To know more about the features of Azure SQL Database, refer to the documentation below from Azure:

- [https://docs.microsoft.com/en-us/azure/azure-sql/database/sql-database-paas-overview](https://docs.microsoft.com/en-us/azure/azure-sql/database/sql-database-paas-overview)

### **Question**  **4**

Domain :Describe how to work with relational data on Azure

Complete the statement.

In Azure SQL databases, transparent data encryption encrypts the ……………..

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Database to protect the data in the motion**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Server to protect the data in the motion**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Database to protect the data at rest**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Server to protect the data at rest**

**Explanation:**

**Correct Answer: C**

Transparent Data Encryption (TDE) protects Azure SQL Database, Azure Synapse Analytics, and Azure SQL Managed Instance against malicious offline activities by encrypting the data at rest. Here, the database, associated backups, and transaction log files at rest can be encrypted and decrypted in real-time without the need for any change in the application.

- **Option A is incorrect**.  Transparent Data Encryption (TDE) protects the data at rest; not in the motion. To protect the data in the motion, transport layer security is used.
- **Option B is incorrect.**  Transparent Data Encryption (TDE) protects the data at rest; not in the motion. To protect the data in the motion, transport layer security is used.
- **Option C is CORRECT.**  Transparent Data Encryption (TDE)  encrypts the database to protects the data at rest.
- **Option D is incorrect. ** Transparent Data Encryption (TDE)  encrypts the database, not the server,  to protects the data at rest.

**Reference:**

To know more about theTransparent Data Encryption (TDE), refer to the documentation below from Azure:

- [https://docs.microsoft.com/en-us/azure/azure-sql/database/transparent-data-encryption-tde-overview?tabs=azure-portal](https://docs.microsoft.com/en-us/azure/azure-sql/database/transparent-data-encryption-tde-overview?tabs=azure-portal)

### **Question**  **5**

Domain :Describe how to work with relational data on Azure

Which of the following is a DML statement?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Create**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Alter**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Insert**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Drop**

**Explanation:**

**Correct Answer: C**

DML statements are the statements that are used to manipulate the data. On the other hand, DDL statements are statements that are used to define the data structure. In simple terms, DDL statements are used to deal with the structure of the database and DML statement are used just to deal with the data, not the structure.

- **Option A is incorrect.**  Create command is used to create a table on the database and therefore is a  DDL command.
- **Option B is incorrect.**  Alter command is used to alter/ change the structure of a  table like adding the column, dropping the column, change datatype or size of a column and rename the column. Therefore, it is a DDL command, not DML.
- **Option C is CORRECT.**  Insert command is used to insert data in the table.  The syntax for Insert is :

INSERT INTO table\_name (column1, column2, .....)
 VALUES (value1, value2, .....)

**Option D is incorrect.**  Drop is again a DDL command that is used to remove an object from the database. For example, Drop table Student can be used to drop the student table from the database and therefore is a DDL statement.

**Reference** _ **:** _

To know more about the DML statements, refer to the documentation below from Azure:

- [https://docs.microsoft.com/en-us/learn/modules/query-relational-data/2-introduction-to-sql](https://docs.microsoft.com/en-us/learn/modules/query-relational-data/2-introduction-to-sql)

### **Question**  **6**

Domain :Describe how to work with relational data on Azure

 What is the significance of Resource governance error &quot;Error: 40544&quot;?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**The database has reached its size quota**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**The service is currently busy**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Session has been terminated because you have a long-running transaction**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**The session has been terminated because of excessive memory usage**

**Explanation:**

**Correct Answer: A**

Error: 40544 indicates that the database has reached its size quota. Some possible resolutions, in this case are - drop the indexes, Partition or delete data or check the documentation for resolutions.

- **Option A is CORRECT. ** Error: 40544 indicates that the database has reached its size quota.
- **Option B is incorrect.**  It is the error _Error 40501 _that indicates that the service is currently busy.
- **Option C is incorrect.**  It is the error _Error 40549 that indicates that the _session has been terminated because you have a long-running transaction
- **Option D is incorrect.**  It is the error _Error 40553 that indicates that _The session has been terminated because of excessive memory usage

**Reference:**

To know more about the common error issues, refer to the documentation below from Azure:

- [https://docs.microsoft.com/en-us/azure/azure-sql/database/troubleshoot-common-errors-issues](https://docs.microsoft.com/en-us/azure/azure-sql/database/troubleshoot-common-errors-issues)

### **Question**  **7**

Domain :Describe how to work with relational data on Azure

In the following SQL query:

INSERT INTO Students ( StudentName , StudentID , Marks , Address) VALUES (&#39;Ram&#39; , 1501,  87, &#39;Delhi&#39;) ;

What are the _ **Students** _ and _ **Marks** _ respectively?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Column and table**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Index and Column**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Table and Primary key**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Table and Column**

**Explanation:**

**Correct Answer:  D**

INSERT is a command in SQL with syntax

INSERT INTO _table name_ ( column 1, column 2, column 3, ……..) VALUES (Value 1, Value 2 , Value 3, ………..). Therefore, in the above-given query, Students is a table and Marks is a column of the Students table.

- **Option A is incorrect**  as according to the syntax for INSERT, Students is the table and Marks is the column.
- **Option B is incorrect**  as Students is a table, not an index. INSERT command is never applied on the indexes.
- **Option C is incorrect ** as in the given SQL query, Marks is a simple column as it is not explicitly defined as the primary key.
- **Option D is CORRECT ** as according to the syntax of INSERT command, Students is the table and Marks is the column.

**Reference:**

To know more, refer to the documentation below from Azure:

- [https://docs.microsoft.com/en-us/learn/modules/query-relational-data/2-introduction-to-sql](https://docs.microsoft.com/en-us/learn/modules/query-relational-data/2-introduction-to-sql)

### **Question**  **8**

Domain :Describe how to work with relational data on Azure

Read theStatement:

Both Azure data studio and SQL Server Management Studio supports all operating systems like windows, macOS and Linux.

The above-given statement is

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A. **True**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B. **False**

**Explanation:**

**Correct Answer: B**

Not all studios supports all operating systems. Windows is the operating system that is supported by both Azure Data Studio andSQL Server Management Studio.  Whereas MacOS and Linux support only Azure data studio,  not SQL Server Management Studio.

- **Option A is incorrect**  as SQL server management studio is only supported by Windows, not by MacOS and Linux.
- **Option B is CORRECT**  as MacOS and Linux support only Azure data studio,  not SQL Server Management Studio.

**Reference:**

To know more about the Azure Data Studio, refer to the documentation below from Azure:

- [https://docs.microsoft.com/en-us/sql/azure-data-studio/what-is-azure-data-studio?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/azure-data-studio/what-is-azure-data-studio?view=sql-server-ver15)

### **Question**  **9**

Domain :Describe how to work with relational data on Azure

Complete the Sentence:

PostgreSQL has its own query language that is known as ……….

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**pgsql**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Oracle**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**SQL**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**MYSQL**

**Explanation:**

**Correct Answer: A**

PostgreSQL has its own query language known as _pgsql_. This query language is a specific variant of the SQL (which is a standard relational query language) that allows to write stored procedures that run/ execute inside the database.

- **Option A is CORRECT. ** Pgsql is a specific variant of SQL that is used by PostgreSQL.
- **Option B is incorrect.**  Oracle is a relational database management system, not any query language.
- **Option C is incorrect.**  SQL is a standard relational query language while pgsql is a specific variant of SQL with some extra features that is used by PostgreSQL.
- **Option D is incorrect**. MYSQL is an open-source relational database management system; not any query language.

**Reference:**

To know more about the PostgreSQL, refer to the documentation below from Azure:

- [https://docs.microsoft.com/en-us/learn/modules/explore-relational-data-offerings/6-postgresql-mariadb-mysql](https://docs.microsoft.com/en-us/learn/modules/explore-relational-data-offerings/6-postgresql-mariadb-mysql)

### **Question**  **10**

Domain :Describe how to work with relational data on Azure

How many deployment options are available for _Azure Database for PostgreSQL_

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**One**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Two**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Three**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Four**

**Explanation:**

**Correct Answer: C**

There are three deployment options available for Azure Database for PostgreSQL. These options are Single-server, Flexible Server (Preview) and Hyperscale.

Single-server deployment option provides and supports the features similar to the Azure Database for MySQL. With this option, the user can select from three available pricing tiers: Basic, General Purpose, and Memory Optimized. These tiers vary in the number of memory, CPUs, and storage sizes and can be selected depending upon the load.

Flexible Server (Preview)  deployment option provides more granular control and flexibility over database management functionalities and configuration settings. It offers better cost optimization control with the capability to stop or start the server and burstable compute tier, ideal for workloads that do not require continuous full compute capacity.

Hyperscale (Citus) is the deployment option that supports large database loads by scaling queries across several server nodes. Here, the database is split across nodes and Data is split into chunks depending upon the value of a sharding or partition key.

- **Option A is incorrect ** as Single server, Flexible Server (Preview) and Hyperscale are the three deployment options available for _Azure Database for PostgreSQL_ .
- **Option B is incorrect**  as Single server, Flexible Server (Preview) and Hyperscale are the three deployment options available for _Azure Database for PostgreSQL._
- **Option C is CORRECT**  as Single server, Flexible Server (Preview) and Hyperscale are the three deployment options available for _Azure Database for PostgreSQL_.
- **Option D is incorrect ** as Single server, Flexible Server (Preview) and Hyperscale are the three deployment options available for _Azure Database for PostgreSQL._

**Reference:**

To know more about the Azure Database for PostgreSQL, refer to the documentation below from Azure:

- [https://docs.microsoft.com/en-us/azure/postgresql/overview](https://docs.microsoft.com/en-us/azure/postgresql/overview)

### **Question**  **11**

Domain :Describe how to work with relational data on Azure

Which of the following is not the specific feature of Azure Database for MySQL?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Elastic scaling**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Automation and monitoring to streamline the management for large-scale deployments**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Protecting the data with automatic backups and point-in-time store for upto 35 days**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Capability of storing and manipulating geometric data, such as polygons, circles, and lines.**

**Explanation:**

**Correct Answer:  D**

Azure Database for MySQL is a relational database service in the Microsoft cloud with the following features:

- Built-in high availability
- Protecting the data with automatic backups and point-in-time store for upto 35 days
- Automated maintenance for the underlying operating system, hardware,  and database engine to maintain the services secured and up to date.
- Predictable performance through inclusive pay-as-you-go pricing.
- Elastic scaling within no significant time
- Cost optimization controls with the ability to stop/start server.
- Industry-leading compliance and Enterprise-grade security for protecting sensitive data-in-motion and at-rest.
- Automation and monitoring to streamline the management for large-scale deployments
- Industry-leading support experience
- **Option A is incorrect ** as Azure Database for MySQL supports Elastic scaling within no significant time.
- **Option B is incorrect**  as Azure Database for MySQL supports automation and monitoring to streamline the management for large-scale deployments.
- **Option C is incorrect**  as Azure Database for MySQL protects the data with automatic backups and point-in-time store for upto 35 days.
- **Option D is CORRECT ** as the Capability of storing and manipulating geometric data, such as polygons, circles, and lines is not the specific feature of Azure database for MYSQL. But it is the feature of Azure Database for PostgreSQL.

**Reference:**

To know more about the Azure Database for SQL, refer to the documentation below from Azure:

- [https://docs.microsoft.com/en-us/azure/mysql/overview](https://docs.microsoft.com/en-us/azure/mysql/overview)
- [https://docs.microsoft.com/en-us/learn/modules/explore-relational-data-offerings/6-postgresql-mariadb-mysql](https://docs.microsoft.com/en-us/learn/modules/explore-relational-data-offerings/6-postgresql-mariadb-mysql)

### **Question**  **12**

Domain :Describe how to work with relational data on Azure

There is a Student Management System with the following &quot;Student&quot; table:

| Student\_Name | Registration\_No | Address |
| --- | --- | --- |
| Rahul | 10301 | Delhi |
| Ram | 10302 | Agra |
| Shyam | 10303 | Noida |

Now, there is a need to change the name of column &quot;Registration\_No&quot; to &quot;Roll\_No&quot;. Which statement you would use?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**UPDATE**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**ALTER**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**CREATE**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**INSERT**

**Explanation:**

**Correct Answer:   B**

For the function like changing the column name, size or datatype, Alter command is used.

Syntax for ALTER:

ALTER TABLE _Tablename_

Rename Column _OldColumnName_ TO _NewColumnName_

- **Option A is incorrect ** as UPDATE statement is used to modify the data; not the name of the column.
- **Option B is CORRECT**  as ALTER statement is used to change the structure of the table. As here we need to rename the column, the following statement can be used;

ALTER TABLE Student

RENAME COLUMN Registration\_No TO Roll\_no ;

- **Option C is incorrect**  as the CREATE statement is used to create the table, not to rename the column.
- **Option D is incorrect**  as INSERT is used to insert the data into the table.

**Reference:**

To know more, refer to the documentation below from Azure:

- [https://docs.microsoft.com/en-us/learn/modules/query-relational-data/2-introduction-to-sql](https://docs.microsoft.com/en-us/learn/modules/query-relational-data/2-introduction-to-sql)

### **Question**  **13**

Domain :Describe how to work with relational data on Azure

A relational database is used when

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**A dynamic Schema is needed**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Data is to be stored in non-tabular form**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**High consistency is needed.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**There is a need to store large videos and images**

**Explanation:**

**Correct Answer:  C**

Dynamic and flexible schema, non-tabular data storage and capability to store large videos and images are the features of non-relational databases. A relational database stores the data in tables and ensures high consistency.

- **Option A is incorrect**  as the dynamic schema is the feature of the non-relational database; not the relational one.
- **Option B is incorrect,**  as in the Relational database, the data is stored in tables. It is a non-relational database where the data is stored in non-tabular form like key-value pairs, graphs, columnars and documents.
- **Option C is CORRECT**  as high consistency is the major feature of Relational databases.
- **Option D is incorrect ** as the Non-relational database is used to store large images and videos.

**References:**

To know more about the Properties of RBDMSs and noSQL databases, refer to the documentation below from Azure:

- [https://docs.rackspace.com/support/how-to/properties-of-rdbmss-and-nosql-databases/](https://docs.rackspace.com/support/how-to/properties-of-rdbmss-and-nosql-databases/)

### **Question**  **14**

Domain :Describe how to work with relational data on Azure

Which of the following Azure tools describes the service(s) to be deployed in JSON (JavaScript Object Notation) format?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Azure Portal**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Azure command-line interface (CLI)**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Azure Powershell**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Azure Resource Manager templates**

**Explanation:**

**Correct Answer : D**

An Azure Resource Manager template describes the service(s) to be deployed in a text file, in  JSON  format. The below is an example template that you can be utilized to provision an instance of Azure SQL Database.

![](RackMultipart20210514-4-cfz1yl_html_dbe9d3258a7032e8.png)

- **Option A is incorrect. **  The Azure portal shows the sequence of service-specific pages that prompt you for the settings needed and confirms these settings before the service is actually provisioned.
- **Option B is incorrect.**  CLI offers a set of commands that can be run from the operating system (OS) command prompt or the Cloud Shell in the Azure portal. These commands can be used for creating and managing the Azure resources.
- **Option C is incorrect.**  Azure PowerShell provides the set of commands that can be used for scripting and automating the administrative tasks. Azure offers a series of commandlets, that are Azure-specific commands,  that can be utilized in PowerShell for creating and managing the Azure resources.
- **Option D is CORRECT.**  An Azure Resource Manager template describes the service(s) to be deployed in a text file, in  JSON  format.

**Reference:**

To know more about the relation data services, refer to the documentation below from Azure:

- [https://docs.microsoft.com/en-us/learn/modules/explore-provision-deploy-relational-database-offerings-azure/2-describe-provision-relational-data-services](https://docs.microsoft.com/en-us/learn/modules/explore-provision-deploy-relational-database-offerings-azure/2-describe-provision-relational-data-services)

### **Question**  **15**

Domain :Describe how to work with non-relational data on Azure

Your organization needs to design a data store that will have Employees data. The data needs to be stored in the below-given format.

| Employee\_Id | Employee\_Information |
| --- | --- |
| 1001 | FName: AronLName: SmithEmail: abc@ajopo.com |
| 1002 | FirstName: BenLast: StokesContact: 123-456-389 |
| 1003 | FirstName: DavidLastName: Hussain |

Which kind of data store would you use?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Document**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Graph**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Columnar**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Key/Value**

**Explanation:**

**Correct Answer: C**

Columnar or column family data store stores the data in form of tables having rows, and dynamic columns. This data store is more flexible than relational databases as here each row does not need to have the same columns. This data store is preferable when there is a need to store a large amount of data and the query patterns are predictable.

- **Option A is incorrect. ** A Document data store stores the data in documents in JSON (JavaScript Object Notation) format. Here, each document has pairs of fields and values. A field value can be a scalar item like number or string, or a compound item like parent-child collection or list. A document has complete data for an entity. For example, an entity can have the details of the customer, order placed by that customer, or both. Below is an example of document data store.

![](RackMultipart20210514-4-cfz1yl_html_1ceec1ed09db9789.png)

- **Option B is incorrect.**  A graph data store provides two types of information in form of nodes and edges. Here, the nodes represent entities, and the edges indicate the relationships among those entities. The following figure shows an example of Graph data store.

![](RackMultipart20210514-4-cfz1yl_html_c1ceed4338c883a5.png)

- **Option C is CORRECT ** as data is available in the format of a table with rows and columns that is the major feature of columnar data type along with additional flexibility in format.
- **Option D is incorrect.**  Key/value store is a kind of large hash table where each data value is associated with a unique key. This key is used to store the data with the help of a hashing function. Below is an example of key-value data store.

![](RackMultipart20210514-4-cfz1yl_html_20f73af64fe37e89.png)

**Reference:**

To know more about the different type of data stores, please refer to the Azure doc below:

- [https://docs.microsoft.com/en-us/azure/architecture/data-guide/big-data/non-relational-data](https://docs.microsoft.com/en-us/azure/architecture/data-guide/big-data/non-relational-data)

### **Question**  **16**

Domain :Describe how to work with non-relational data on Azure

Read the statement below:

You should use Azure File Storage for the files that are likely to be written by multiple concurrent processes simultaneously.

Choose the correct option.

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A. **True**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B. **False**

**Explanation:**

**Correct Answer: B**

It is never recommended to use Azure File Storage for the files that are likely to be written by multiple concurrent processes simultaneously. Multiple writers need careful synchronization, otherwise, the updates or changes performed by one process are likely to be overwritten by other processes. The possible option is to lock the file while it is in writing mode, and as the write operation is complete release the lock. But, this option can highly impact the concurrency and limit performance.

**Reference:**

To know more about the Azure File Storage, please refer to the Azure documentation:

- [https://azure.microsoft.com/en-in/blog/azure-file-storage-now-generally-available/](https://azure.microsoft.com/en-in/blog/azure-file-storage-now-generally-available/)

### **Question**  **17**

Domain :Describe how to work with non-relational data on Azure

At which of the following levels, it is possible to set the throughput for an Azure Cosmos DB account? (Select two options)

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)A.

**Partition**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)B.

**Database**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)C.

**Container**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)D.

**Item**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)E.

**Value**

**Explanation:**

**Correct Answers: B and C**

With Azure Cosmos DB, throughput can be provisioned at two granularities: Azure Cosmos containers and Azure Cosmos databases. Provisioned throughput can be of two types - standard (manual) or auto-scale.

- **Option A is incorrect.**  With Azure Cosmos DB, the throughput can be provisioned only at two levels: Database and container.
- **Option B is CORRECT**. With Azure Cosmos DB it is possible to provision the throughput at the database level.
- **Option C is CORRECT. ** With Azure Cosmos DB it is possible to provision the throughput at the container level.
- **Option D is incorrect.**  With Azure Cosmos DB, the throughput can be provisioned only at two levels: Database and container.
- **Option E is incorrect. ** With Azure Cosmos DB, the throughput can be provisioned only at two levels: Database and container.

**Reference:**

To know more about the Azure Cosmos Account, please refer to the Azure documentation:

- [https://docs.microsoft.com/en-us/azure/cosmos-db/set-throughput](https://docs.microsoft.com/en-us/azure/cosmos-db/set-throughput)

### **Question**  **18**

Domain :Describe how to work with non-relational data on Azure

Which of the following API of Azure Cosmo Database provides a graph-based view on database?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**MongoDB API**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Cassandra AP**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Gremlin**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Table API**

**Explanation:**

**Correct Answer: C**

Cosmo DB supports 5 APIs: Core (SQL) API, MongoDB API, Cassandra API, Table API, and Gremlin API.

Core (SQL) API is the default API that provides a view of that data that resembles a traditional NoSQL document store. SQL like language is used to query the hierarchical JSON documents with a SQL-like language.

MongoDB is a document database that has its own programmatic interface. Therefore, the data structure associated with MangoDB is JSON documents. Cassandra is a column family database management system that supports querying data through Cassandra Query Language (CQL).

Gremlin provides a graph-based view of the database. It means that the data is either a vertex (an individual item in the database), or an edge (a relationship between the database items).

- **Option A is incorrect.**  MongoDB is a document database that has its own programmatic interface. Therefore, data structure associated with MangoDB is JSON documents.
- **Option B is incorrect.**  Cassandra is a column family database management system that supports querying data through Cassandra Query Language (CQL).
- **Option C is CORRECT. ** Gremlin provides a graph-based view of the database. It means that the data is either a vertex (an individual item in the database), or an edge (a relationship between the database items ).
- **Option D is incorrect.**  Table API allows using the Azure Table Storage API to store and retrieve the documents. The associated data structure with Table API is key-value.

**Reference:**

To know more about the API for Azure Cosmos Database, please refer to the Azure documentation:

- [https://docs.microsoft.com/en-us/learn/modules/choose-api-for-cosmos-db/2-identify-the-technology-options](https://docs.microsoft.com/en-us/learn/modules/choose-api-for-cosmos-db/2-identify-the-technology-options)

### **Question**  **19**

Domain :Describe how to work with non-relational data on Azure

Match the common error status code with their significance

**Status Code**                  **Description / Significance**

a) 401                          1) Service Unavailable

b) 408                          2) Too many Requests

c) 429                          3) Request timed out

d) 503                          4) Not authorized

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**a1 b2 c3 d4**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**a3 b2 c1 d4**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**a4 b3 c2 d1**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**a2 b4 c3 d1**

**Explanation:**

**Correct Answer: C**

401- Not authorized

408- Request Timed out

429- Too many Requests

503- Service Unavailable

Error HTTP 401 states that &quot;the MAC signature found in the HTTP request is not the same as the computed signature&quot;.

Error HTTP 408 happens if the SDK was unable to complete the request before the timeout limit occurred.

Error HTTP 429 indicates that the requests are being throttled.

Error HTTP 503 indicates that the SDK was not able to connect to Azure Cosmos DB.

**Reference:**

To know more, please refer to the Azure documentation:

- [https://docs.microsoft.com/en-us/azure/cosmos-db/troubleshoot-dot-net-sdk](https://docs.microsoft.com/en-us/azure/cosmos-db/troubleshoot-dot-net-sdk)

### **Question**  **20**

Domain :Describe how to work with non-relational data on Azure

Which of the following is the right sequence for CosmosDB levels demonstrating the strongest consistency to Lowest consistency (means the first level in sequence having the strongest consistency and the last level showing the least consistency)?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Strong, Bounded staleness, Consistent prefix, Session, and Eventual**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Strong, Session, Consistent prefix, Bounded staleness, and Eventual**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Strong, Bounded staleness, Session, Consistent prefix and Eventual**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Strong, Bounded staleness, Session, Eventual and Consistent prefix**

**Explanation:**

**Correct Answer: C**

Azure Cosmos DB supports 5 well-defined levels varying in term of consistency, latency, availability and throughput. Here are the 5 levels from strongest to weakest:  Strong, Bounded staleness, Session, Consistent prefix, and Eventual.

Each level offers performance and availability tradeoffs. The following image demonstrates the various consistency levels as a spectrum.

![](RackMultipart20210514-4-cfz1yl_html_1141e06e0a5a90eb.png)

**Strong consistency: ** With this option, the client sees the writes only after the modification/changes are confirmed as written successfully to all replicas. Uncommitted or partial writes are never visible to the clients. Strong consistency option is unavailable if there is a need for distributing the data across multiple global regions.

**Bounded Staleness: ** With this option, there is a lag between writing and reading the updated data. While choosing bounded staleness, staleness can be defined in two ways;

1. number of versions (K) of item
2. The time interval (T) reads might lag behind the writes

**Session: ** During a single client session, reads are certain to honor the consistent-prefix, monotonic reads and writes, read-your-writes, and write-follows-reads guarantees. It considers a single &quot;writer&quot; session or sharing the session token for many writers.

**Consistent Prefix: ** This option guarantees that changes appear in order, although there is a possible delay before they are visible. Within that period, the applications are likely to see old data.
**Eventual Consistency: ** This is weakest consistency option with no ordering guarantee for reads.  A client may read the values even older than the ones it had read before. This consistency option is suitable for the applications that don&#39;t need any ordering guarantees. Examples are count of Retweets,  non-threaded comments or likes.

**Reference:**

To know more about the different levels supported by Azure Cosmos DB, please refer to the Azure documentation:

- [https://docs.microsoft.com/en-us/azure/cosmos-db/consistency-levels](https://docs.microsoft.com/en-us/azure/cosmos-db/consistency-levels)

### **Question**  **21**

Domain :Describe how to work with non-relational data on Azure

Which of the followings can be used to set the IP firewall on the Azure Cosmos DB account?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Azure portal**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Azure Resource Manager template**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

  **Azure CLI**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

  **Azure PowerShell**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]E.

**All of the above**

**Explanation:**

**Correct Answer: E**

IP firewall can be set on Azure Cosmos DB account through any of the following ways:

- Using the Azure portal
- Declaratively through an Azure Resource Manager template
- Programmatically using the Azure CLI or Azure PowerShell by updating the  **ipRangeFilter**  property

**1.Configuring IP firewall through Azure Portal**

Go to the Azure Cosmos DB account page and on the navigation menu, choose  **Firewall and virtual networks**. update the  **Allow access from**  value to  **Selected networks** , and finally click  **Save**.

![](RackMultipart20210514-4-cfz1yl_html_ecefaff18a3e6550.png)

**2. Configuring an IP firewall through a Resource Manager template**

while configuring access control to Azure Cosmos DB account, ensure that the Resource Manager template specifies the  **ipRules**  property with an array of allowed IP ranges. The  **ipRules**  property was added with API version 2020-04-01. In earlier versions,  **ipRangeFilter**  property is exposed, that is a list of comma-separated IP addresses.

Example to demonstrate how the  **ipRules**  property is exposed in API version 2020-04-01 or later:

![](RackMultipart20210514-4-cfz1yl_html_c4db943ad0770ab.png)

Example to demonstrate API version prior to 2020-04-01

![](RackMultipart20210514-4-cfz1yl_html_73262781ac7ea4f9.png)

**3. Configuring an IP access control policy through Azure CLI**

![](RackMultipart20210514-4-cfz1yl_html_47a2882993f025cf.png)

**4. Configuring an IP access control policy through PowerShell**

![](RackMultipart20210514-4-cfz1yl_html_14660b3189fad05c.png)

**Reference:**

To know more about how to configure firewall, please refer to the Azure documentation:

- [https://docs.microsoft.com/en-us/azure/cosmos-db/how-to-configure-firewall#troubleshoot-ip-firewall](https://docs.microsoft.com/en-us/azure/cosmos-db/how-to-configure-firewall%23troubleshoot-ip-firewall)

### **Question**  **22**

Domain :Describe how to work with non-relational data on Azure

A system is required to built to monitor the temperature throughout a number of office blocks, and set the air conditioning in every room in every block to have a pleasant temperature. Your system needs to manage the air conditioning in many thousand buildings throughout the country, and each building has at least 110 air-conditioned rooms. What kind of NoSQL data store is most suitable to capture the temperature data so that it can be processed quickly?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Storing the data in a file stored in a share, created through Azure File Storage.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Send the data to an Azure Cosmos DB database and utilize Azure Functions for processing the data.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Use blobs to write the temperatures in Azure Blob storage.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Use table to store temperature**

**Explanation:**

**Correct Answer: B**

Azure Cosmos DB is capable to ingest huge volumes of data quickly. A thermometer in every room can send the temperature data to an Azure Cosmos DB database. An Azure Function can be run as each and every item is stored. This function can check the temperature, and activate a remote process for configuring the air conditioning in the rooms.

- **Option A is incorrect. ** There will be a need of separate processes in every room or building to capture the data in the file. Although data can be read by multiple processes simultaneously from a file stored in Azure File Storage, it is the multiple writers that can create problems, and the writes done by one process can be overwritten by another that will result in losing the data.
- **Option B is CORRECT.** AzureCosmos DB is capable to ingest huge volumes of data quickly. A thermometer in every room can send the temperature data to a Azure Cosmos DB database. An Azure Function can be run as each and every item is stored. This function can check the temperature, and activate a remote process for configuring the air conditioning in the rooms.
- **Option C is incorrect**. For the given scenario, blob storage is not a good option.
- **Option D is incorrect**. For the given scenario, table storage is not a good option.

**Reference:**

To know more, please refer to the Azure documentation:

- [https://docs.microsoft.com/en-us/azure/cosmos-db/migrate-cosmosdb-data](https://docs.microsoft.com/en-us/azure/cosmos-db/migrate-cosmosdb-data)

### **Question**  **23**

Domain :Describe how to work with non-relational data on Azure

Which of the following is a benefit of using multi-region replication with Cosmos DB?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Increased Availability**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Consistent data in every region**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Enhanced data security**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**None of these**

**Explanation:**

**Correct Answer: A**

With Multi-region replication in Cosmos DB, data is replicated across multiple regions that increases the availability. If a region is inaccessible, the data is still available in other regions and can be retrieved from there.

- **Option A is CORRECT.**  With Multi-region replication in Cosmos DB data is replicated across multiple regions that increases the availability.
- **Option B is incorrect.**  It is the availability, not the consistency, that is the benefit of multi-region replication with Cosmos DB.
- **Option C is incorrect**  as it&#39;s the encryption that enhances data security. Availability, not the enhanced data security, is the benefit of multi-region replication with cosmos DB.
- **Option D is incorrect**  as increased availability is the benefit of using multi-region replication with Cosmos DB.

**Reference** :

To know more about the benefit of using multi-region replication with Cosmos DB, please refer to the Azure documentation:

- [https://docs.microsoft.com/en-us/azure/cosmos-db/distribute-data-globally](https://docs.microsoft.com/en-us/azure/cosmos-db/distribute-data-globally)

### **Question**  **24**

Domain :Describe an analytics workload on Azure

Consider the statements below:

S1: Bring data into Power BI Desktop, and create a report

S2: Publish to the Power BI service, where you can create new visualizations or build dashboards

S3: Share dashboards with others, especially people who are on the go

S4: View and interact with shared dashboards and reports in Power BI Mobile apps.

Which of the following sequence of the above statements represents the common flow of activities in Power BI?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**S1-S2-S4-S3**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**S2-S1-S3-S4**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**S1-S2-S3-S4**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**S2-S3-S1-S4**

**Explanation:**

**Correct Answer: C**

The activities and analyses in Power BI generally follow a common flow as given below:

1. Bring data into Power BI Desktop, and create a report.
2. Publish to the Power BI service, where you can create new visualizations or build dashboards.
3. Share dashboards with others, especially people who are on the go.
4. View and interact with shared dashboards and reports in Power BI Mobile apps.

So, the sequence S1-S2-S3-S4 is the right sequence.

- **Option A is incorrect**  as in normal flow, Share dashboards with others, especially people who are on the go comes before View and interact with shared dashboards and reports in Power BI Mobile apps.
- **Option B is incorrect**  as it is Bring data into Power BI Desktop, and create a report, not Publish to the Power BI service, where you can create new visualizations or build dashboards, that is the first activity in the normal flow.
- **Option C is correct**. Bring data into Power BI Desktop, and create a report, Publish to the Power BI service, where you can create new visualizations or build dashboards, Share dashboards with others, especially people who are on the go, and finally  View and interact with shared dashboards and reports in Power BI Mobile apps is the common flow in Power BI.
- **Option D is incorrect**  as Bring data into Power BI Desktop, and create a report is the first activity in the normal flow. The right sequence of common flow is - Bring data into Power BI Desktop, and create a report, Publish to the Power BI service, where you can create new visualizations or build dashboards, Share dashboards with others, especially people who are on the go and finally  View and interact with shared dashboards and reports in Power BI Mobile apps is the common flow in Power BI.

**Reference:**

To know more about Power BI, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/get-started-with-power-bi/2-using-power-bi](https://docs.microsoft.com/en-us/learn/modules/get-started-with-power-bi/2-using-power-bi)

### **Question**  **25**

Domain :Describe an analytics workload on Azure

Which of the following element of Azure Synapse enables you to access all the Synapse Analytics tools?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Synapse Spark pool**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Synapse pipelines**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Synapse Link**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Synapse Studio**

**Explanation:**

**Correct Answer: D**

Synapse SQL pool, Synapse Spark pool, Synapse Pipelines, Synapse Link, and Synapse Studio are the elements of Azure Synapse. Out of these elements, Synapse Studio ** ** is a web user interface that enables the data engineers to access all the Synapse Analytics tools. Synapse Studio can be used for creating SQL and Spark pools, defining and running pipelines, and configuring links to external data sources.

- **Option A is incorrect.**  Synapse Spark Pool is the element that supports Azure Machine Learning through integration with the AzureML and SparkML packages.
- **Option B is incorrect. ** A Synapse pipeline represents a logical grouping of activities that collectively perform a task. The activities of the pipeline define the actions to be performed on your data.
- **Option C is incorrect**. Synapse Link is the component that enables you to connect to Azure Cosmos DB. It can be used to perform/run near real-time analytics over the operational data stored in an Azure Cosmos DB.
- **Option D is correct.**  Synapse Studio ** ** is a web user interface that enables data engineers to access all the Synapse Analytics tools. Synapse Studio can be used for creating SQL and Spark pools, defining and running pipelines, and configuring links to external data sources.

**Reference:**

To know more about the Azure Synapse, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-data-storage-processing-azure/3-explore-azure-synapse-analytics](https://docs.microsoft.com/en-us/learn/modules/explore-data-storage-processing-azure/3-explore-azure-synapse-analytics)

### **Question**  **26**

Domain :Describe an analytics workload on Azure

Which of the following services is useful to ingest data into Azure Synapse Analytics?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Power BI**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Azure Data Factory**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Azure Active Directory**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Azure Databricks**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]E.

**Azure Data Lake Storage**

**Explanation:**

**Correct Answer: B**

Azure Data Factory is a _data integration service_ that supports retrieving data from one or multiple data sources, and converting it into the desired format that you process. It can also be used to ingest data into Azure Synapse Analytics from almost every source.

- **Option A is incorrect.**  Power BI is an analytics tool that can be utilized to report on the data within Azure Synapse Analytics.
- **Option B is correct.**  Azure Data factory can be used to ingest data into Azure Synapse Analytics from almost every source.
- **Option C is incorrect.**   Azure Active Directory is an authentication method. It is not a data ingestion framework that could be used to ingest data into Azure Synapse Analytics.
- **Option D is incorrect. ** Azure Databricks is an Apache Spark environment that runs on Azure to offer big data processing, streaming, and machine learning.
- **Option E is incorrect. ** Azure Data Lake Storage is a secure cloud platform that offers cost-effective and scalable storage for big data analytics.

**Reference** :

To know more about Azure Data Factory, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/azure/data-factory/introduction](https://docs.microsoft.com/en-us/azure/data-factory/introduction)

### **Question**  **27**

Domain :Describe an analytics workload on Azure

You have retrieved data formatted in a different format from multiple sources. Now, you need to transform the data into a single uniform format. Which of the following data services would you use?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Azure Data Factory**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Azure Data Lake Storage**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Azure Databricks**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**None of These**

**Explanation:**

**Correct Answer: A**

Azure Data Factory is a _data integration service_ that allows users to retrieve data from one or multiple data sources, and convert it into the desired format. The various data sources might have different data representation and have _a noise_ that is needed to be filtered out. Azure Data Factory allows to extract only the interesting/required data, and discard the rest.  Even if the interesting data is not presented in the required format for processing by other services, it can be transformed into the desired format.

![](RackMultipart20210514-4-cfz1yl_html_5c2fd1f5cc30ec3a.png)

- **Option A is correct.**  Azure Data Factory allows transforming the data from multiple sources in the desired uniform format.
- **Option B is incorrect.**  Azure Data Lake Storage is a secure cloud platform that offers cost-effective and scalable storage for big data analytics. In an Azure Data Services data warehouse solution, data is generally loaded into Azure Data Lake Storage before it is processed into a structure that supports efficient analysis in Azure Synapse Analytics.
- **Option C is incorrect.**  Azure Databricks is an Apache Spark environment that runs on Azure to offer big data processing, streaming, and machine learning.
- **Option D is incorrect**. Azure Data Factory allows users to transform the data from multiple sources in the desired uniform format.

**Reference** :

To know more about Azure Data Factory, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/examine-components-of-modern-data-warehouse/3-explore-azure-data-services-warehousing](https://docs.microsoft.com/en-us/learn/modules/examine-components-of-modern-data-warehouse/3-explore-azure-data-services-warehousing)

### **Question**  **28**

Domain :Describe an analytics workload on Azure

In which of the following case, you would recommend Azure Synapse Analytics? (You can choose multiple options)

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)A.

**To perform complex queries and aggregations**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)B.

**To create a dashboard from the tabular data**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)C.

**To allow a large number of users to query analytics data**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)D.

**To quickly process very large amounts of data.**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)E.

**To retrieve data from multiple data sources**

**Explanation:**

**Correct Answers: A and D**

Azure Synapse Analytics incorporates SQL technologies, Transact-SQL query capabilities, and open-source Spark tools to support the quick processing of very large amounts of data. SQL pools in Synapse Analytics are helpful in complex reporting. You can utilize the full power of Transact-SQL to run complex SQL statements or queries that summarize and aggregate the data.

- **Option A is correct**. Azure Synapse Analytics is optimized to perform compute-intensive tasks like complex queries and aggregations.
- **Option B is incorrect**. Azure Analysis Services, not Azure Synapse, is used to create dashboards.
- **Option C is incorrect.**  Azure Synapse Analytics is optimized to perform compute-intensive operations instead of the high level of query concurrency.
- **Option D is correct.**  Azure Synapse Analytics incorporates SQL technologies, Transact-SQL query capabilities, and open-source Spark tools to support the quick processing of very large amounts of data.
- **Option D is incorrect.**  Azure Data Factory, not Azure Synapse Analytics is used to retrieve data from one or multiple data sources, and convert it into the desired format.

**Reference:**

To know more about Azure Synapse Analytics, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-data-storage-processing-azure/3-explore-azure-synapse-analytics](https://docs.microsoft.com/en-us/learn/modules/explore-data-storage-processing-azure/3-explore-azure-synapse-analytics)

### **Question**  **29**

Domain :Describe an analytics workload on Azure

Which of the following is the main difference between a data warehouse and a data lake?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**A data warehouse contains raw business data whereas a data lake holds structured information**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**A data warehouse stores the dynamic data whereas a data lake stores the static data**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**A data warehouse contains structured information whereas a data lake holds raw business data**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**A data warehouse is highly accessible and easy to update whereas data lake is complicated while making changes**

**Explanation:**

**Correct Answer: C**

A data lake is a repository for a huge amount of raw data. As the data is raw and unprocessed, it supports quick loading and updating but due to lack of structure, it does not support efficient analysis. Also, a data lake is highly accessible and it is easy to update the data lake. A data warehousing solution transforms the raw data of a data lake into meaningful business information in a data warehouse.

- **Option A is incorrect.**  A data warehouse contains structured information, not the raw data, whereas a data lake holds the raw business data, not the structured information.
- **Option B is incorrect.**   The data and information held by both the data warehouse and data lake will change over time with the ingestion and processing of new data.
- **Option C is correct.**  A data warehouse contains structured information whereas a data lake holds raw business data. A data warehousing solution transforms the raw data of a data lake into meaningful business information in a data warehouse.
- **Option D is incorrect.**  A data lake is highly accessible and easy to update whereas a data warehouse is complicated and it is costly to make changes in the data warehouse.

**Reference:**

To learn more about Azure Data Warehouse and Azure Data Lake, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/introduction-to-azure-data-lake-storage/](https://docs.microsoft.com/en-us/learn/modules/introduction-to-azure-data-lake-storage/)
- [https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/data-warehousing](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/data-warehousing)

### **Question**  **30**

Domain :Describe an analytics workload on Azure

Which of the following statements is/are true for batch processing? (Select Multiple)

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)A.

**It processes a large volume of data all at once**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)B.

**data is always processed in real-time**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)C.

**There is no or significantly low latency**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)D.

**there is an expected latency**

**Explanation:**

**Correct Answers: A and D**

Batch [data processing](https://www.7wdata.be/vocabulary/data-processing/) is an effective method of processing a huge amount of [data](https://www.7wdata.be/vocabulary/data/) where a set of [transactions](https://www.7wdata.be/vocabulary/database-transaction/) is collected over a time period. It involves collecting, entering, and processing data and eventually producing the batch results.  In batch processing, latency is common.

- **Option A is correct.**  Batch processing processes the large volume of data all at once.
- **Option B is incorrect.**  It is real-time data processing that processes the data in real-time.
- **Option C is incorrect**. It is real-time processing where there is no or very low latency.
- **Option D is correct.**  In batch processing, there are the expected latencies.

**References:**

To know more about Batch Data Processing, please refer to the URLs below:

- [https://www.bmc.com/blogs/what-is-batch-processing-batch-processing-explained/](https://www.bmc.com/blogs/what-is-batch-processing-batch-processing-explained/)
- [https://www.7wdata.be/business-analytics/batch-vs-real-time-data-processing/](https://www.7wdata.be/business-analytics/batch-vs-real-time-data-processing/)

### **Question**  **31**

Domain :Describe an analytics workload on Azure

 Which of the following are the features of transactional data? (Select 4 Options)

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)A.

**Denormalized data**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)B.

**Tabular data**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)C.

**Multidimensional model**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)D.

**Appendable and updateable**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)E.

**Low integrity and consistency**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)F.

**Schema on write**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)G.

**Pessimistic or optimistic Locking strategy**

**Explanation:**

**Correct Answers:  B, D, F and G**

Transactional data is data or information that tracks the interactions associated with the activities of an organization. These interactions are generally business transactions, like payments done by the customers, payments done to suppliers, items moving through inventory, orders received, or services delivered. Transactional data has the following features:

- Highly normalized
- Supports user transactions
- Schema on write, strongly enforced
- Updatable and appendable
- Strong consistency and ACID guarantees
- Pessimistic or optimistic locking strategy
- High integrity and flexibility
- Optimized workload with heavy writes and moderate reads
- Primary and secondary indexing
- Small to medium-sized datum
- Relational model with tabular transactional data
- Small (MBs) to Large (a few TBs) Scaling
- **Option A is incorrect.**  Normalization is one of the most common features of transactional data. It is OLAP where data is denormalized for improving the query performance when aggregation is to be done.
- **Option B is correct.**   Transactional data is in tabular form.
- **Option C is incorrect**. Transactional data uses the relational model; not the multidimensional model.
- **Option D is correct.**  Transactional data is appendable and updatable.
- **Option E is incorrect.**  Transactional data has high integrity and consistency.
- **Option F is correct.**  Schema on write, strongly enforced is one of the common features of transactional data.
- **Option G is correct.**  In transactional data, the locking strategy is pessimistic or optimistic.

**Reference:**

To know more about Transactional Data, please refer to the URL below:

- [https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/online-transaction-processing](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/online-transaction-processing)

### **Question**  **32**

Domain :Describe an analytics workload on Azure

Select the right sequence for implementing the Extract, Load, and Transform (ELT) process.

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Extract the source data into text files, Prepare the data for loading, Load the data into staging tables with PolyBase or the COPY command, Land the data into Azure Blob storage or Azure Data Lake Store, Transform the data, Insert the data into production tables.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Extract the source data into text files, Land the data into Azure Data Lake Store or Azure Blob storage, Prepare the data for loading, Load the data into staging tables with PolyBase or the COPY command, Transform the data, Insert the data into production tables.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Extract the source data into text files, Land the data into Azure Blob storage or Azure Data Lake Store, Prepare the data for loading, Load the data into staging tables with PolyBase or the COPY command, Insert the data into production tables, Transform the data.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Extract the source data into text files, Prepare the data for loading, Load the data into staging tables with PolyBase or the COPY command, Land the data into Azure Blob storage or Azure Data Lake Store, Insert the data into production tables, Transform the data.**

**Explanation:**

**Correct Answer: B**

ELT is a process that extracts the data from a source system, loads it into a SQL pool, and then transforms it.

The basic steps for implementing the Extract, Load, and Transform (ELT) process are:

1. Extract the source data into text files.
2. Land the data into Azure Data Lake Store or Azure Blob storage.
3. Prepare the data for loading.
4. Load the data into staging tables through PolyBase or the COPY command.
5. Transform the data.
6. Insert the data into the production tables.

**References:**

To know more about the implementation of the Extract, Load, and Transform (ELT) process, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/design-elt-data-loading](https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/design-elt-data-loading)

### **Question**  **33**

Domain :Describe an analytics workload on Azure

 ……………….. is an open-source and parallel-processing framework that supports in-memory processing to improve the performance of big-data analysis applications.

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

[**Apache Hadoop**](https://docs.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-introduction)

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Apache Storm**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Apache Kafka**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Apache Spark**

**Explanation:**

**Correct Answer: D**

HDInsight supports specific cluster types and cluster customization capabilities like the capability to add components, languages, and utilities. The various cluster types offered by HDInsight are - Apache Hadoop, Apache Spark, Apache HBase, ML Services, Apache Storm, Apache Interactive Query, and Apache Kafka. Out of these, Apache Spark is an open-source and parallel-processing framework that supports in-memory processing to improve the performance of big-data analysis applications.

- **Option A is incorrect.**  Apache Hadoop is a  framework that utilizes HDFS, a simple MapReduce programming model, and YARN resource management for processing and analyzing the batch data in parallel.
- **Option B is incorrect.**  Apache Storm is a distributed and real-time computation system that processes large streams of data very quickly.
- **Option C is incorrect.**  Apache Kafka is an open-source platform that is optimized to build streaming data pipelines and applications.
- **Option D is correct. **  Apache Spark is an open-source and parallel-processing framework that supports in-memory processing to improve the performance of big-data analysis applications.

**Reference:**

To know more about the HDInsight, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-overview](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-overview)

### **Question**  **34**

Domain :Describe an analytics workload on Azure

Which of the following statements is false?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**In a Spark pool, the nodes are replaced with a Spark cluster.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**The number of nodes is specified while creating the Spark cluster.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**A Spark pool doesn&#39;t have any auto scaling option.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**The Spark cluster splits the work out into a sequence of parallel tasks that could be performed concurrently.**

**Explanation:**

**Correct Answer: C**

The statement &quot;A Spark pool doesn&#39;t have any auto scaling option&quot; is incorrect. Because Spark pools have an auto scaling option that can be enabled so that pools scale by removing or adding the nodes as per requirements. Autoscaling can occur while processing is active.

- **Option A is incorrect.**   It is true that in a Spark pool, the nodes are replaced with a spark cluster.
- **Option B is incorrect**. In the Spark pool, the number of nodes is specified while creating the Spark cluster.
- **Option C is correct.**  Spark pools have an auto scaling option that can be enabled so that pools scale by removing or adding the nodes as per requirements. Autoscaling can occur while processing is active.
- **Option D is incorrect**.  The Spark cluster indeed splits the work out into a sequence of parallel tasks that could be performed concurrently.

**Reference:**

To know more about Spark pool, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/examine-components-of-modern-data-warehouse/3-explore-azure-data-services-warehousing](https://docs.microsoft.com/en-us/learn/modules/examine-components-of-modern-data-warehouse/3-explore-azure-data-services-warehousing)

### **Question**  **35**

Domain :Describe an analytics workload on Azure

In Power BI, ……………….  is a collection of preset and ready-made visuals and reports that are shared with the entire organization.

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**An App**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**The Canvas**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Scheduled Refresh**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Gateway Connection**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]E.

**Parameters**

**Explanation:**

**Correct Answer: A**

In Power Bi, an app is a collection of preset and ready-made visuals and reports that are shared with an entire organization. The app is as easy to use as ordering a fast-food value meal or microwaving a TV dinner where you just need to make a few comments or press a few buttons and you are provided with a set of entrees designed to go together and all presented in a tidy and readymade package.

- **Option A is correct.**   It is an app in Power Bi that is a collection of preset and ready-made visuals and reports that are shared with the entire organization.
- **Option B is incorrect**. It is an app, not canvas, that is a collection of preset and ready-made visuals and reports. Instead, the _canvas_ is the area in the center of the Power BI service that displays the available data sources in the Power BI service. This area is blank until visuals or reports are created.
- **Option C is incorrect**. Scheduled refresh is not a collection of preset and ready-made visuals and reports. Rather, it allows the user to automatically update the data for datasets.
- **Option D is incorrect**. Gateway Connection is not a collection of preset and ready-made visuals and reports. Rather, it allows the user to automatically update the data for datasets.
- **Option E is incorrect**. The parameter is not a collection of preset and ready-made visuals and reports. Rather, it allows the user to automatically update the data for datasets.

**Reference:**

To know more about Power BI, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/get-started-with-power-bi/4-exercise-touring-and-using-power-bi](https://docs.microsoft.com/en-us/learn/modules/get-started-with-power-bi/4-exercise-touring-and-using-power-bi)

### **Question**  **36**

Domain :Describe an analytics workload on Azure

In Data Lake Analytics, which of the following languages is used to define a job that contains queries to transform data and extract insights?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**SQL**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**C#**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**U-SQL**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**PL/SQL**

**Explanation:**

**Correct Answer: C**

Data Lake Analytics provides a framework and collection of tools that is used to analyze data stored in Microsoft Azure Data Lake Store and other repositories. You write the jobs consisting of queries to transform the data and get insights. The language that is used to write these jobs is known as &quot;U-SQL&quot;. U-SQL is a hybrid language that has the features of both languages SQL and C#, and offers the procedural and declarative capabilities that can be used for data processing.

- **Option A is incorrect.**  It is U-SQL, not SQL, that is used to define the mentioned jobs in data lake analytics.
- **Option B is incorrect**. It is U-SQL, not #C, that is used to define the mentioned jobs in data lake analytics.
- **Option C is correct.**  U-SQL is the language that is used to define a job that contains queries to transform data and extract insights into data lake analytics.
- **Option D is incorrect.**  It is U-SQL, not PL/SQL, that is used to define the mentioned jobs in data lake analytics.

**References:**

To know more, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-data-storage-processing-azure/2-describe-azure](https://docs.microsoft.com/en-us/learn/modules/explore-data-storage-processing-azure/2-describe-azure)

### **Question**  **37**

Domain :Describe an analytics workload on Azure

Which of the following statement(s) is/are true about Data Lake Store? (Select Multiple)

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)A.

**Azure Data Lake Store offers a file system that is capable of storing only a limited amount of data.**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)B.

**Azure Data Lake Store is optimized for analytics workloads.**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)C.

**Azure Data Lake Store is not compatible with the Hadoop Distributed File System (HDFS).**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)D.

**Azure Data Lake Store offers granular security over data, through Access Control Lists (ACL).**

**Explanation:**

**Correct Answers:  B and D**

Data Lake Store offers a file system that is capable of storing near-limitless quantities of data.  It supports holding massive amounts of raw data (blobs) and structured data. Data Lake Store is optimized for analytics workloads. It has compatibility with the Hadoop Distributed File System (HDFS). Hadoop jobs can be run through Azure HDInsight that can write and read data in the Data Lake Store efficiently. Azure Data Lake Store offers granular security over data, through Access Control Lists (ACL) which specifies which folders or files in the store can be accessed through which accounts.

- **Option A is incorrect**.  Data Lake Store is capable of storing near-limitless quantities of data. You can hold huge amounts of raw data (blobs) and structured data.
- **Option B is correct**. Azure Data Lake Store is optimized for analytics workloads.
- **Option C is incorrect.**  Azure Data lake Store is compatible with the Hadoop Distributed File System (HDFS). Hadoop jobs can be run through Azure HDInsight that can write and read data in the Data Lake Store efficiently.
- **Option D is correct.**  Azure Data Lake Store offers granular security over data, through Access Control Lists (ACL) which specifies which folders or files in the store can be accessed through which accounts.

**Reference:**

To know more about Azure Data Lake Store, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-data-storage-processing-azure/2-describe-azure](https://docs.microsoft.com/en-us/learn/modules/explore-data-storage-processing-azure/2-describe-azure)

### **Question**  **38**

Domain :Describe an analytics workload on Azure

Which of the following objects can be added to a Microsoft Power BI dashboard? (Select 3 Options)

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)A.

**Microsoft PowerPoint Slide**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)B.

**Report Page**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)C.

**Visualization from a Report**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)D.

**Textbox**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)E.

**Data Flow**

**Explanation:**

**Correct Answers: B, C and D**

It is possible to add a report page, a visualization from a report, textbox, web content, image, video, and streaming data to a Microsoft Power BI Dashboard. You can&#39;t add the objects like Microsoft PowerPoint slides or data flow to a Microsoft Power BI Dashboard.

- **Option A is incorrect.**  It is not possible to add a Microsoft PowerPoint slide to a Microsoft PowerPoint Slide.
- **Option B is correct.**  It is possible to add a report page to a Microsoft Power BI dashboard.
- **Option C is correct.**  It is possible to add visualization from a report to a Microsoft Power Bi Dashboard.
- **Option D is correct.**  A textbox can be easily added to a Microsoft Power BI dashboard.
- **Option E is incorrect.**  It is not possible to add a data flow to a Microsoft Power BI dashboard.

**References:**

To know more about Microsoft Power BI Dashboard, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/power-bi/consumer/end-user-dashboards](https://docs.microsoft.com/en-us/power-bi/consumer/end-user-dashboards)
- [https://docs.microsoft.com/en-us/power-bi/create-reports/service-dashboard-add-widget](https://docs.microsoft.com/en-us/power-bi/create-reports/service-dashboard-add-widget)

### **Question**  **39**

Domain :Describe core data concepts

The mathematical terms  **Relation**  and  **Tuple**  in relational database respectively represent

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Table and Domain**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Table and Row**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Table and column**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Key and Row**

**Explanation:**

**Correct Answer: B**

In a relational database, data is stored in the form of tables. Entities are modeled as tables and each instance of an entity is represented by a row in the table and the column represents the attributes of that entity.  In mathematical terms, a table is known as a Relation, and rows are known as tuples.

- **Option A is incorrect.**  In a relational database, a relation refers to the table whereas a tuple represents a row in the table. A domain is the set of permitted values for an attribute.
- **Option B is correct.**  In a relational database, a Relation refers to the table whereas a Tuple refers to the row.
- **Option C is incorrect.**  In a relational database, a relation refers to the table whereas a tuple represents a row in the table. A column represents the set of values of the same data type for various instances of an entity.
- **Option D is incorrect.**  In a relational database, a relation refers to the table whereas a tuple represents a row in the table. There are many types of keys like primary key, secondary key, alternate keys, etc that have their purpose. A primary key is the most common key that uniquely identifies each row in the table.

**References:**

To know more about the characteristics of the Relational Database, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/describe-concepts-of-relational-data/2-explore-characteristics](https://docs.microsoft.com/en-us/learn/modules/describe-concepts-of-relational-data/2-explore-characteristics)

### **Question**  **40**

Domain :Describe core data concepts

Which of the following property ensures that the concurrent execution of multiple transactions leaves the database in the same state that would have been attained if the transactions were executed sequentially?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Atomicity**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Consistency**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Isolation**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Durability**

**Explanation:**

**Correct Answer: C**

A transactional database needs to adhere to the ACID (Atomicity, Consistency, Isolation, Durability) properties which ensure that the database remains consistent while processing transactions.

Out of these properties, isolation is the one that ensures the concurrent execution of multiple transactions leaves the database in the same state that would have been attained if the transactions were executed sequentially. A concurrent process can&#39;t see the data in an inconsistent state. For example, there is a transaction of transferring money from one account to another. The money has been deducted from one account but not yet credited to another.

- **Option A is incorrect.**  _Atomicity_ ensures that each transaction is considered as a single _unit_, which either succeeds or fails completely. If any statement of a transaction is failed to complete, the whole transaction is considered failed and the state of the database remains unchanged.
- **Option B is incorrect.**  _Consistency_ ensures that a transaction can only take the data in the database from one valid state to another. A consistent database should never create or lose data in such a way that can&#39;t be accounted for.
- **Option C is correct.**  Isolation ensures that the concurrent execution of multiple transactions leaves the database in the same state that would have been attained if the transactions were executed sequentially.
- **Option D is incorrect**. Durability ensures that once a transaction has been committed, the changes made by that transaction will survive permanently even if there is a system failure such as a service outage or crash, etc.

**Reference** :

To know more, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-core-data-concepts/3-identify-types-storage](https://docs.microsoft.com/en-us/learn/modules/explore-core-data-concepts/3-identify-types-storage)

### **Question**  **41**

Domain :Describe core data concepts

Which of the following are the characteristics of a relational database?

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)A.

**All data needs to be stored as integers**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)B.

**The rows in a table consist of one or more columns that represent the properties of the entity.**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)C.

**The different rows in the same table might have different columns.**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)D.

**A tuple in a relation represents a single entity.**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)E.

**A relational database has a flexible schema.**

**Explanation:**

**Correct Answers:  B and D**

In a relational database, the entities are modeled as the tables. Entities are the things for which the information needs to be stored or known. For example, in an organization, you might be interested in storing the information regarding employees, department and project, etc. All these employees, department and project are known as entity types, and tables are created for those. Each row in a table represents the one instance of that entity type. For example, in the EMPLOYEE table, each row represents the detail of one employee.  Below is a snapshot of the database with table EMPLOYEE, DEPARTMENT, and PROJECT.

![](RackMultipart20210514-4-cfz1yl_html_a0ef0d127e91cd1f.png)

![](RackMultipart20210514-4-cfz1yl_html_232ac3a8941104c2.png)

![](RackMultipart20210514-4-cfz1yl_html_5ee68c53f8ef0f02.png)

- **Option A is incorrect.**  All the data don&#39;t need to be stored as integers. Data can be stored as any data type integer, real number, string, Date, etc.
- **Option B is correct. ** In a relational database, the rows in a table consist of one or more columns that represent the properties of the entity.
- **Option C is incorrect. **  In a table, all the rows need to have the same columns although the values for different rows might be the same or different depending upon the attribute.
- **Option D is correct.**  A Row or Tuple in a table represents the one instance or entity of a particular entity type.
- **Option E is incorrect.**  Schemaless design in the property of the non-relational database, not the relational database.

**Reference:**

To know more about the characteristics of a Relational Database, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/describe-concepts-of-relational-data/2-explore-characteristics](https://docs.microsoft.com/en-us/learn/modules/describe-concepts-of-relational-data/2-explore-characteristics)

### **Question**  **42**

Domain :Describe core data concepts

Which of the following is/are the examples of streaming dataset? (Select 2 Options)

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)A.

**Data from Twitter feeds**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)B.

**Sales data of a company for last month**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)C.

**Data from sensors and devices**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)D.

**List of employees employed in an organization**

**Explanation:**

**Correct Answers: A and C**

A streaming dataset is the collection of data that is published continuously. In stream processing, each piece of new incoming data is processed when it arrives. Streaming handles the data in real-time.

- **Option A is correct. ** Data from Twitter feeds is a streaming dataset as the data on Twitter is published continuously.
- **Option B is incorrect. ** Sales data for the last month is not an example of a streaming dataset as this data is a point in time dataset.
- **Option C is correct. ** Data from sensors and devices is an example of a streaming dataset as this data is published on a continuous basis.
- **D is incorrect**. In the company, there are a finite number of employees and the number of employees in the organization doesn&#39;t change very frequently like minute to minute. Therefore, the List of employees employed in an organization is not an example of a streaming dataset.

**Reference:**

To know more about streaming datasets, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-core-data-concepts/4-describe-difference](https://docs.microsoft.com/en-us/learn/modules/explore-core-data-concepts/4-describe-difference)

### **Question**  **43**

Domain :Describe core data concepts

Choose the right type of the following graph.

![](RackMultipart20210514-4-cfz1yl_html_5ab8449d0a3debbc.png)

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Bar chart**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Pie chart**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Tree map**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Line Chart**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]E.

**Scatter Chart**

**Explanation:**

**Correct Answer: B**

A pie chart displays the division of the total amount among different categories as a circle divided into radial slices. A single slice in the circle represents a category and the size of the slice represents the proportion of that category out of the total.

- **Option A is incorrect. **  A [bar](https://chartio.com/learn/charts/bar-chart-complete-guide/) chart displays numeric values against different categories in a 2-axis plot. One axis lists the category levels and for each category, one bar is plotted, and the length of the bar along the other axis represents the numeric value assigned to that category.

![](RackMultipart20210514-4-cfz1yl_html_80da1867c6a5410e.png)

_Figure: An example of bar chart_

- **Option B is correct. ** As in the above diagram, the categories and their share are denoted by the slices of the circle. The above diagram is an example of a Pie chart.
- **Option C is incorrect. ** Treemap is a chart of colored rectangles where size represents the relative value of each item. They can be hierarchical, with rectangles nested within the main rectangles.

![](RackMultipart20210514-4-cfz1yl_html_6fbfea165b6c605b.png)

_Figure: An example of TreeMap_

- **Option D is incorrect. ** The line chart emphasizes the overall shape of an entire series of values, generally over time.

![](RackMultipart20210514-4-cfz1yl_html_8e8a957945a12223.png)

_Figure: Example of a Line Chart_

- **Option E is incorrect.**  A scatter chart displays the relationship between two numerical values.

![](RackMultipart20210514-4-cfz1yl_html_a3cb1b30556ba14b.png)

_Figure: An example of Scatter chart_

**References:**

To know more, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-concepts-of-data-analytics/3-explore-data-visualization](https://docs.microsoft.com/en-us/learn/modules/explore-concepts-of-data-analytics/3-explore-data-visualization)
- [https://chartio.com/learn/charts/how-to-choose-pie-chart-vs-bar-chart/](https://chartio.com/learn/charts/how-to-choose-pie-chart-vs-bar-chart/)

### **Question**  **44**

Domain :Describe core data concepts

Which type of analytics is appropriate to tell what will happen in the future?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Descriptive analytics**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Diagnostic analytics**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Predictive analytics**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Prescriptive analytics**

**Explanation:**

**Correct Answer: C**

Predictive analytics helps in answering the questions regarding what will happen in the future. Here historical data is utilized to identify trends and determine if they might recur. Predictive analytical tools offer valuable insight into what may occur in the future.

- **Option A is incorrect**. Descriptive analytics helps in answering the questions regarding what has happened, depending upon the historical data.
- **Option B is incorrect.**  Diagnostic analytics helps in answering questions regarding why things happened, not about what might happen in the future.
- **Option C is correct.**  Predictive analytics helps in answering the questions regarding what will happen in the future.
- **Option D is incorrect.**  Prescriptive analytics helps in answering the questions regarding what actions should be taken to reach a goal or target.

**References:**

To know more, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-concepts-of-data-analytics/4-explore](https://docs.microsoft.com/en-us/learn/modules/explore-concepts-of-data-analytics/4-explore)

### **Question**  **45**

Domain :Describe core data concepts

In which pipeline, the transformation happens in the target datastore?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**ETL**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**ELT**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**None of these**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**None**

**Explanation:**

**Correct Answer: B**

In the ELT (Extract, Load, and Transform) pipeline, the transformation happens in the target datastore. Rather than utilizing a separate transformation engine, the processing capabilities of the target datastore are utilized to transform data. However, ELT is efficient only when the target system is enough powerful to transform the data efficiently.

![](RackMultipart20210514-4-cfz1yl_html_1893e8e1b44d10ef.png)

- **Option A is incorrect.**  Extract, transform, and load (ETL) pipeline is utilized to collect data from multiple sources, transform the data as per business rules, and eventually load it into a destination data store. The transformation process in ETL occurs in a specialized engine, and typically involves utilizing staging tables to temporarily hold data as it is being transformed and eventually loaded to its destination. Therefore, in ETL, transformation does not happen in the target data store.
- **Option B is correct.**  ELT (Extract, Load, and Transform) is a data pipeline where the transformation happens in the target datastore. Rather than utilizing a separate transformation engine, the processing capabilities of the target datastore are utilized to transform data.

**Reference:**

To know more about the ELT (Extract, Load, and Transform), please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/etl](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/etl)

### **Question**  **46**

Domain :Describe core data concepts

……………..  is the process of transforming and mapping the raw data into a more useful format for analysis?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Data Cleaning**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Data Ingestion**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Wrangling**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Data Analysis**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]E.

**Data Modeling**

**Explanation:**

**Correct Answer: C**

Wrangling is the process of transforming and mapping raw data into a more useful format for analysis. It might include writing code for capturing, filtering, cleaning, combining, and aggregating data from multiple sources.

- **Option A is incorrect.**  Data cleaning is a generalized term that comprises a wide range of actions like removing or deleting anomalies and applying filters and transformations that would be too time-taking to run during the ingestion phase.
- **Option B is incorrect.**  Data ingestion is the process that obtains and imports the data for immediate use or storage in a database.
- **Option C is correct.**  Wrangling is the process of transforming and mapping raw data into a more useful format for analysis.
- **Option D is incorrect.**  Data analysis is the process of inspecting, cleansing, transforming, and modeling data to get useful information, supporting decision-making, and informing conclusions.
- **Option E is incorrect.**  Data modeling is a process of creating a conceptual representation of the data objects, in association with other data objects, and the rules between them.

**Reference:**

To know more about wrangling, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-concepts-of-data-analytics/2-describe-data-ingestion-process](https://docs.microsoft.com/en-us/learn/modules/explore-concepts-of-data-analytics/2-describe-data-ingestion-process)

### **Question**  **47**

Domain :Describe core data concepts

Choose the visual that depicts the major contributors to a selected value or result?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Bar and Column chart**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Matrix Chart**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Treemap**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Key Influencers**

**Explanation:**

**Correct Answer: D**

A key influencer chart depicts the major contributors to a selected value or result. Key influencers help a lot in understanding the factors that influence a key metric. For example, it is a good choice to know why sales were so high in last month or what influences the clients to place a 2nd order.

![](RackMultipart20210514-4-cfz1yl_html_e689d42bba36f6a9.png)

_Figure: An example of a key influencer chart_

- **Option A is incorrect.**  Bar and column charts are a good choice to know how a set of variables varies across different categories. These are the key influencers, not bar or column charts, that depict the major contributors to a selected value or result.
- **Option B is incorrect.**  A matrix is a tabular visual that summarizes data. It does not help in depicting the major contributors to a selected value or result.
- **Option C is incorrect**. A treemap is a chart of colored rectangles where size represents the relative value of each item. They can be hierarchical, with rectangles nested within the main rectangles.
- **Option D is correct. A**  key influencer chart depicts the major contributors to a selected value or result. Key influencers help a lot to understand the factors that influence a key metric.

**Reference:**

To know more, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-concepts-of-data-analytics/3-explore-data-visualization](https://docs.microsoft.com/en-us/learn/modules/explore-concepts-of-data-analytics/3-explore-data-visualization)

### **Question**  **48**

Domain :Describe core data concepts

Which of the following statement is true?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Prescriptive Analytics helps in learning what might occur if circumstances change, and how to handle these situations while cognitive analytics help in answering the questions about what steps or actions should be taken to reach a goal or target.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Cognitive analytics helps in learning what might occur if circumstances change, and how to handle these situations while Prescriptive Analytics helps in answering the questions about what steps or actions should be taken to reach a goal or target.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Predictive Analytics helps in answering the questions about what steps or actions should be taken to reach a goal or target while cognitive analytics helps in learning what might occur if circumstances change, and how to handle these situations.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Cognitive analytics helps in answering the questions about what steps or actions should be taken to reach a goal or target while Predictive Analytics helps in learning what might occur if circumstances change, and how to handle these situations.**

**Explanation:**

**Correct Answer: B**

Data Analytics activities can be categorized as _descriptive_, _diagnostic_, _predictive_, _prescriptive_, and _cognitive_ analytics.  The various data analytics activities with their specific purposes can be understood from the following table:

![](RackMultipart20210514-4-cfz1yl_html_ba0e48ea1df08e83.png)

- **Option A is incorrect**. It is cognitive Analytics, not prescriptive Analytics, that helps in learning what might occur if circumstances change, and how to handle these situations while it is prescriptive analytics, not cognitive analytics, that help in answering the questions about what steps or actions should be taken to reach to a goal or target.
- **Option B is correct. ** Cognitive analytics helps in learning what might occur if circumstances change, and how to handle these situations while Prescriptive Analytics helps in answering the questions about what steps or actions should be taken to reach a goal or target.
- **Option C is incorrect.**  It is Prescriptive Analytics, not Predictive Analytics, that helps in answering the questions about what steps or actions should be taken to reach to a goal or target while cognitive analytics helps in learning what might occur if circumstances change, and how to handle these situations.
- **Option D is incorrect.**  It is prescriptive analytics, not cognitive analytics, that helps in answering the questions about what steps or actions should be taken to reach to a goal or target while Cognitive Analytics, not Predictive Analytics, helps in learning what might occur if circumstances change, and how to handle these situations.

**References** :

To know more about different types of analytics activities, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-concepts-of-data-analytics/4-explore](https://docs.microsoft.com/en-us/learn/modules/explore-concepts-of-data-analytics/4-explore)

### **Question**  **49**

Domain :Describe core data concepts

Which of the following are the roles and responsibilities of a database administrator? (Choose 3 Options)

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)A.

**To install and upgrade the database server and application tools.**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)B.

**To enroll the users and maintain system security.**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)C.

**To develop, construct, test, and maintain the databases and data structures.**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)D.

**To monitor and optimize the performance of the database**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)E.

**To Prepare the data for prescriptive and predictive modeling**

**Explanation:**

**Correct Answers: A, B and D**

Database Administrator is tasked to manage and organize the databases. The main job of a database administrator is to ensure that data is available and protected from loss, theft, and corruption and is easily accessible whenever needed. The following figure shows the common roles and responsibilities of a database administrator:

- To install and upgrade the database server and application tools.
- To allocate system storage and plan storage needs for the database system.
- To modify the database structure, as necessary, from information provided by application developers.
- To enroll the users and maintain system security.
- To ensure compliance with the database vendor license agreement.
- To control and monitor user access to the database.
- To monitor and optimize the performance of the database.
- To do Planning for backup and recovery of database information.
- To maintain archived data.
- To ensure Backing up and restoring databases.
- To contact database vendor for technical support.
- To generate various reports from the database using appropriate queries as per needs.
- To manage and monitor data replication.
- **Option A is correct**. To install and upgrade the database server and application tools is one of the common roles and responsibilities of a database administrator.
- **Option B is correct**. To enroll the users and maintain system security is one of the common roles and responsibilities of a database administrator.
- **Option C is incorrect.**  To develop, construct, test, and maintain the databases and data structures is the responsibility of the data engineer, not the data administrator.
- **Option D is correct.**  To monitor and optimize the performance of the database is one of the common roles and responsibilities of a database administrator.
- **Option E is incorrect.**  To Prepare the data for prescriptive and predictive modeling is the responsibility of the data engineer, not the data administrator

**References:**

To know more about the roles and responsibilities of a Data Administrator, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-roles-responsibilities-world-of-data/3-review-tasks-tools-for-database-administration](https://docs.microsoft.com/en-us/learn/modules/explore-roles-responsibilities-world-of-data/3-review-tasks-tools-for-database-administration)
- [https://docs.microsoft.com/en-us/learn/modules/explore-roles-responsibilities-world-of-data/4-review-tasks-tools-for-data-engineering](https://docs.microsoft.com/en-us/learn/modules/explore-roles-responsibilities-world-of-data/4-review-tasks-tools-for-data-engineering)

### **Question**  **50**

Domain :Describe core data concepts

Which of the following is not a data job role?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Data Engineer**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Data Analyst**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**System Administrator**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Database Administrator**

**Explanation:**

**Correct Answer: C**

Systems administrators are the ones who deal with infrastructure components like networks, virtual machines, and other physical devices in a data center.

- **Option A is incorrect. ** Data Engineer is the one who works with data, apply data filtering and cleaning algorithms, identify business rules, and convert the data into useful information.
- **Option B is incorrect.**  The main role of a data analyst is exploring and analyzing the data to create charts and other visualizations that help an organization to make informed decisions.
- **Option C is correct**. A system administrator is the one who deals with infrastructure components, not the data.
- **Option D is incorrect**. The Database Administrator is responsible to manage and organize the databases. The main job of a database administrator is to ensure that data is available and protected from loss, theft, and corruption and is easily accessible whenever needed.

**Reference:**

To know more about data job roles, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-roles-responsibilities-world-of-data/2-explore-job-roles](https://docs.microsoft.com/en-us/learn/modules/explore-roles-responsibilities-world-of-data/2-explore-job-roles)

### **Question**  **51**

Domain :Describe how to work with non-relational data on Azure

How many performance tiers are offered by Azure File Storage?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**1**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**2**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**3**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**4**

**Explanation:**

**Correct Answer: B**

Standard tier and Premium tier are 2 performance tiers offered by Azure File Storage. These tiers vary in terms of throughput and cost. The _Standard_ tier utilizes hard disk-based hardware in a data center while the _Premium_ tier utilizes solid-state disks.  The _Premium_ tier provides higher throughput than the standard tier but the cost of a premium tier is also higher than the standard one.

- **Option A is incorrect.**  Azure File Storage offers 2 performance tiers, not 1.
- **Option B is correct**. Standard tier and Premium tier are 2 performance tiers offered by Azure File Storage.
- **Option C is incorrect.**  Azure File Storage offers 2 performance tiers i.e. standard tier and Premium tier, not three.
- **Option D is incorrect.**  Azure File Storage offers 2 performance tiers i.e. standard tier and Premium tier, not four.

**Reference:**

To know more about Azure File Storage, please refer to the Azure documentation below:.

- [https://docs.microsoft.com/en-us/learn/modules/explore-non-relational-data-offerings-azure/4-explore-azure-file-storage](https://docs.microsoft.com/en-us/learn/modules/explore-non-relational-data-offerings-azure/4-explore-azure-file-storage)

### **Question**  **52**

Domain :Describe how to work with non-relational data on Azure

Name the elements of an Azure Table storage key.

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**Row key and column key**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**Partition key and Row key**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**Column name and Table name**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**Column name and Column key**

**Explanation:**

**Correct Answer: B**

Two elements of an Azure Table Storage key are the partition key and the Row key. The partition key is the key that identifies the partition having the row and a row key is unique for each row in a given partition. In a partition, the items are stored in row key order.

- **Option A is incorrect.**  Columns in an Azure table storage table are anonymous and have no name or key. Partition key and Row key are two elements of an Azure Table Storage Key.
- **Option B is correct**. Partition key and Row key are two elements of an Azure Table Storage Key where the partition key identifies a specific partition and the row key identifies the row in a given partition.
- **Option C is incorrect**. Columns in an Azure table storage table are anonymous and have no name or key. The partition key and row key are the elements of an Azure Table storage key.
- **Option D is incorrect**. Columns in an Azure table storage table are anonymous and have no name or key.

**Reference:**

To know more about Azure Table storage, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-non-relational-data-offerings-azure/2-explore-azure-table-storage](https://docs.microsoft.com/en-us/learn/modules/explore-non-relational-data-offerings-azure/2-explore-azure-table-storage)

### **Question**  **53**

Domain :Describe how to work with non-relational data on Azure

Which of the following are the advantages of using Azure Table Storage tables over other methods of data storage? (Select 3 Options)

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)A.

**It ensures consistency as transactional updates across multiple entities are guaranteed**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)B.

**There is no requirement of mapping and maintaining the complex relationships typically required by a normalized relational database**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)C.

**Referential integrity is the major benefit of Azure Table Storage tables that maintains the relationships between rows**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)D.

**Tables can store semi-structured data**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)E.

**It is simpler to scale. It consumes the same time to insert data in an empty table or a table with billions of entries. An Azure storage account can consist of up to 500 TB of data**

**Explanation:**

**Correct Answers: B, D and E**

The tables in Azure Table Storage are schemaless. Data can be easily adapted as per the need of the application. Tables can hold flexible datasets like user data for web applications, device information, address books, or other kinds of metadata your service needs. The important thing is to select the partition and row keys carefully.

The main advantages of using Azure Table Storage tables over other methods of data storage are:

- It is simpler to scale. It consumes the same time to insert data in an empty table or a table with billions of entries. An Azure storage account can consist of up to 500 TB of data.

- Tables can store semi-structured data.
- There is no requirement of mapping and maintaining the complex relationships typically required by a normalized relational database.
- Row insertion is easy and fast.
- Data retrieval is also  fast  if the row and partition keys are specified as query criteria

The main disadvantages of using Azure Table Storage tables are:

- Consistency might be an issue as it does not guarantee transactional updates across multiple entities.
- There is no concept of referential integrity. The relationships between rows are maintained externally to the table
- Filtering and sorting on non-key data is quite difficult. Queries, where non-key fields are searching criteria, might result in full table scans.
- **Option A is incorrect**. Consistency is not the benefit, rather an issue in Azure table storage tables as it does not guarantee transactional updates across multiple entities.
- **Option B is correct.**  In Azure table storage tables, there is no requirement of mapping and maintaining the complex relationships typically required by a normalized relational database.
- **Option C is incorrect**. In Azure table storage tables, there is no concept of referential integrity. The relationships between rows are maintained externally to the table.
- **Option D is correct**. Azure table storage tables can hold semi-structured data which is also an advantage of Azure table storage tables.
- **Option E is correct**. Scaling is easy in Azure table storage tables. It consumes the same time to insert data in an empty table or a table with billions of entries. An Azure storage account can consist of up to 500 TB of data.

**Reference:**

To know more about Azure Table storage, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/learn/modules/explore-non-relational-data-offerings-azure/2-explore-azure-table-storage](https://docs.microsoft.com/en-us/learn/modules/explore-non-relational-data-offerings-azure/2-explore-azure-table-storage)

### **Question**  **54**

Domain :Describe how to work with non-relational data on Azure

Choose the correct statement(s).

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)A.

**In an on-Premises solution, Application level controls and Network Controls are the responsibility of cloud customers and physical security is the responsibility of cloud providers.**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)B.

**In SaaS solutions, Application level controls and Network Controls are the responsibility of cloud customers and physical security is the responsibility of cloud providers.**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)C.

**In SaaS solutions, Application level controls, Network Controls, and physical security are the responsibilities of the cloud provider.**

![](RackMultipart20210514-4-cfz1yl_html_5a5c7b5cacf9205.gif)D.

**In IaaS solution, Application level controls are the responsibility of cloud customers while it is the responsibility of the cloud provider in the SaaS solution.**

**Explanation:**

**Correct Answers: C and D**

Data security is a shared responsibility between cloud customers and database providers. Depending upon the chosen database provider, the amount of responsibility varies. The following diagram depicts the responsibilities of cloud customers and cloud providers in different types of solutions.

![](RackMultipart20210514-4-cfz1yl_html_fe3ed10874337ddb.png)

- **Option A is incorrect.**   As shown in the above diagram, in the case of an on-premises solution, everything from end-point protection to physical security is the responsibility of cloud customers.
- **Option B is incorrect**.  As shown in the above diagram, in a SaaS solution, Application level controls, Network Controls, and physical security is the responsibility of the cloud provider.
- **Option C is correct.**  As shown in the above diagram, in a SaaS solution, Application level controls, Network Controls, and physical security are the responsibilities of the cloud provider.
- **Option D is correct.**   As shown in the above diagram, in the IaaS solution, Application level controls are the responsibility of cloud customers while it is the responsibility of cloud providers in SaaS solutions.

**Reference:**

To know more, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/azure/cosmos-db/database-security](https://docs.microsoft.com/en-us/azure/cosmos-db/database-security)

### **Question**  **55**

Domain :Describe how to work with non-relational data on Azure

Which of the following statement is false about Azure Cosmos DB?

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]A.

**It supports providing or restricting access to the Cosmos account, database, container, and offers (throughput) using Access control (IAM) in the Azure portal.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]B.

**It supports monitoring the account for normal and abnormal activities.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]C.

**All connections to Azure Cosmos DB support HTTPS.**

![](RackMultipart20210514-4-cfz1yl_html_6f2da339620346d2.gif)]D.

**The data once deleted can&#39;t be recovered in any way.**

**Explanation:**

**Correct Answer: D**

Azure Cosmos DB secures the database through

- Network security and firewall settings
- User authentication and fine-grained user controls
- Replicating data globally for regional failures
- Ability to failover from one data center to another
- Local data replication within a data center
- Automatic data backups
- restoring the deleted data from backups
- isolating and protecting the sensitive data
- Responding to attacks
- Monitoring for attacks
- Geo-fencing data to adhere to data governance restrictions
- Physical protection of servers in protected data centers
- Certifications
- **Option A is incorrect.**  In Azure Cosmos DB, you can provide or restrict access to the Cosmos account, container, database, and offers (throughput) through Access control (IAM) in the Azure portal. IAM offers role-based access control and integrates with Active Directory. You can utilize built-in or even the custom roles for groups as well as individuals.
- **Option B is incorrect.**  Azure Cosmos DB allows monitoring the account for normal and abnormal activities using [audit logging and activity logs](https://docs.microsoft.com/en-us/azure/cosmos-db/monitor-cosmos-db). You can see what operations have been carried out on your resources, who started the operation, when the operation happened and the status of the operation, etc.
- **Option C is incorrect**. In Azure Cosmos DB, all connections to Azure Cosmos DB support HTTPS.
- **Option D is correct.**  It is false that the data once deleted can&#39;t be recovered in Azure Cosmos DB. It supports recovering data you might have accidentally deleted up to ~30 days after the event through automated online backups.

**Reference** :

To know more about Azure Cosmos DB, please refer to the Azure documentation below:

- [https://docs.microsoft.com/en-us/azure/cosmos-db/database-security](https://docs.microsoft.com/en-us/azure/cosmos-db/database-security)
