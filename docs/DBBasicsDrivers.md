#### What is the Difference Between ODBC OLEDB and JDBC

The main difference between ODBC OLEDB and JDBC is that the ODBC is an API developed by Microsoft to access relational databases 
and OLEDB is an API developed by Microsoft to access both relational and non-relational databases while JDBC is an API developed by Oracle to access the relational and non-relational database.
  
  
> When developing software, it is necessary to connect the application to the database. For example, assume a medical centre management system. The programmer has to write the code to insert, update and delete patient records, doctor records, etc. 
These systems always exchange data with a database.
ODBC, OLEDB and JDBC are three APIs that allow connecting the application to a database in order to access data.  


### Key Areas Covered
1. What is ODBC
     – Definition, Features
2. What is OLEDB
     – Definition, Features
3. What is JDBC
     – Definition, Feature
4. What is the Difference Between ODBC OLEDB and JDBC
     – Comparison of Key Differences
     
     
#### What is ODBC
> ODBC stands for Open Database Connectivity. It is a standard Application Programming Interface (API) that allows accessing the DBMS using SQL.
Moreover, an application can use ODBC functions using the ODBC driver manager. The driver can pass queries to the DBMS. An application that uses ODBC is called an ODBC compliant.
Furthermore, ODBC allows maximum interoperability. In other words, a single application can access different DBMSs. 
Users can add ODBC drivers to connect the application to the required DBMS.     


![Fig: ODBC](https://pediaa.com/wp-content/uploads/2019/02/Difference-Between-ODBC-OLEDB-and-JDBC_Figure-2.png)


ODBC interface includes a Library of ODBC with function calls (Core functions and extended functions). It also provides a standard set of error codes and a way of connecting and logging to a DBMS. Overall, ODBC works as an interface to exchange data among various applications and data sources


##### What is OLEDB
OLEDB stands for Object Linking and Embedding Database. It is an API that helps to access data from different sources in a uniform manner. It is based on Component Object Model (COM) and is a part of Microsoft Data Access Components (MDAC) stack. OLEDB is advanced than ODBC as it is capable of accessing data from non-relational databases that do not use SQL.

Moreover, OLEDB divides data sources from the application. It is because different applications require different types of data and it is not important to know how to access them with all technical methods. There are two major sections in OLEDB called consumer and provider. The consumer obtains data while the provider gives data to the consumers.

##### What is JDBC
JDBC stands for Java Database Connectivity. It is an API that provides database-independent connectivity between the Java application and different databases. It is available in Java Standard Edition (Java SE). JDBC allows Java programs to access enterprise-level data. With the support of the JDBC driver, it is possible to access data in dissimilar environments as well.



![JDBC image](https://pediaa.com/wp-content/uploads/2019/02/Difference-Between-ODBC-OLEDB-and-JDBC_Figure-1.png)


When connecting a Java application to a database, it is necessary to go through the below steps.

• Load the driver to connect to the database.
• Create a connection to communicate with the database object
• Execute the required SQL statements
• Return the result set

#### Difference Between ODBC OLEDB and JDBC
Definition
ODBC is a standard application programming interface (API) for accessing Database Management Systems (DBMS). OLEDB, on the other hand, is an API that allows accessing data from a variety of sources in a uniform manner while JDBC is an API for the programming language Java, which defines how a client may access a database. Thus, this is the main difference between ODBC OLEDB and JDBC.

##### Long Form
ODBC stands for Open Database Connectivity while OLEDB stands for Object Linking and Embedding Database, and JDBC stands for Java Database Connectivity.

##### Developer
Another difference between ODBC OLEDB and JDBC is their developer. Microsoft is the developer of both ODBC and OLEDB while Oracle is the developer of JDBC.

##### Related Databases
ODBC works with relational databases while OLEDB and JDBC work with relational and non-relational databases. Hence, this is another difference between ODBC OLEDB and JDBC.

#### Conclusion
The main difference between ODBC OLEDB and JDBC is that the ODBC is an API developed by Microsoft to access relational databases while OLEDB is an API developed by Microsoft to access both relational and non-relational databases, and JDBC is an API developed by Oracle to access the relational and non-relational database

