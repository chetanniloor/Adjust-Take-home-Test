# Adjust-Take-home-Test
CREATE TABLE table1(val Varchar);
INSERT into table1(val) VALUES(5);
INSERT into table1(val) VALUES(3);
INSERT into table1(val) VALUES(6);
INSERT into table1(val) VALUES(7);
INSERT into table1(val) VALUES(9);
INSERT into table1(val) VALUES(10);
INSERT into table1(val) VALUES(7);
SELECT CONCAT(MIN(val), "-->", MAX(val)) AS min_to_max FROM table1;

NOTE----I have tried my level best to answer it, I guess there is a another way to this by  "creating a user-defined aggregate function whose implementation is defined in a class of an assembly in the .NET Framework. For the Database Engine to bind the aggregate function to its implementation, the .NET Framework assembly that contains the implementation must first be uploaded into an instance of SQL Server by using a CREATE ASSEMBLY statement."

 Although the Test was for Database Engineer and the position which I am given is in JD and applied is for DBA(Database Administrator)-PostgreSQL. 
