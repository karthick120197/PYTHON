# PYTHON
# Python MYSQL Database (Python and sql database connetction).
# INSTALLATION:
pip apt install pymysql
# open python
import pymysql
# CONNECTING PYTHON AND MYSQL
a=pymysql.cursor("hostlocal","root","password","Database_Name")
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
