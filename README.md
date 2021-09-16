# RDS-AWS

Amazon Relational Database Service (Amazon RDS) is a web service that makes it easier to set up, operate, and scale a relational database in the AWS Cloud.

Steps to create an RDS-

```

1. Create the RDS Database instance

2. Do the port opening in security group.

3. Connect to your RDS Instance with your system CLI and create a table .
$ mysql -h <endpoint> -P <port number>-u <user name> -p 
$ CREATE TABLE sample (firstname varchar(20), lastname varchar (20)); 

```
