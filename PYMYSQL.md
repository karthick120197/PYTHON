# PYTHON
# Python MYSQL Database (Python and sql database connetction).
# INSTALLATION:
pip apt install pymysql
# Create sql table
create database Bluebus;
create table Bus_info(Bus_no int not null,Bus_name varchar(50) not null, Bus_type varchar(20) not null, Bus_capacity int not null,Travels_id int not null);
# open python
import pymysql
# CONNECTING PYTHON AND MYSQL
import pymysql.cursors

# Connect to the database
a= pymysql.connect(host='localhost',
                             user='user',
                             password='passwd',
                             db='db',
                             charset='utf8mb4',
                             cursorclass=pymysql.cursors.DictCursor)
# CONNECTING TO THE TABLE
a
#
cursor=a.cursor()
# FOR PRINTING CURSOR.EXECUTE IS USED EXAMPLE:
cursor.execute("show tables")
# TO SELECT THE TABLES
cursor.fetch()
# TO PRINT THE DATA IN THE TABLE
cursor.execute("select * from table")
# TO PRINT SPECIFIC ROW
pritn(row["row_Number"])
print (row[1])
# FOR CLOSING THE CONNECTION
a.close()
