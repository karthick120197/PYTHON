#LINK TO THE HTML FILE
file:///C:/Users/Karthick/Downloads/car_services(3).html

#CODES
import pandas as pd
import csv
a=pd.read_csv("C:/Users/Karthick/Downloads/Check-In.csv")
b=pd.read_csv("C:/Users/Karthick/Downloads/Check-Out.csv")
a.head(5)
b.head(5)
b = b.dropna(axis=0)
b.head(7)
merged = a.merge(b, on='sno')
merged
df=pd.DataFrame(merged)
df
from IPython.display import HTML
import numpy as np
import base64
create_download_link(df)
engine = sqlalchemy.create_engine('mysql+pymysql://root:sgk123@localhost:3306/car')
df = pd.read_sql_table('customer_feedback',engine)
df
query='''select * from customer_feedback inner join servicestable11 on (customer_feedback.sno=servicestable11.sno)'''
df = pd.read_sql_query(query,engine)
df
query='''SELECT AVG(Total_cost) FROM servicestable11'''
df = pd.read_sql_query(query,engine)
df
query="""SELECT count(checkin_time) from servicestable11 where DATE_FORMAT(checkin_time, '%%H')<=10 """query=''' select car_number, count(1) from servicestable11 group by car_number having count(*)>1'''
df=pd.read_sql_query(query,engine)
df
df=pd.read_sql_query(query,engine)
df
query=''' select car_number, count(1) from servicestable11 group by car_number having count(*)>1'''
df=pd.read_sql_query(query,engine)
df
query="""SELECT count(checkin_time) from servicestable11 where DATE_FORMAT(checkin_time, '%%W')="saturday" """
df=pd.read_sql_query(query,engine)
df
query='''select count(sno), Type_of_car from servicestable11 group by Type_of_car'''
df=pd.read_sql_query(query,engine)
df
query=''' select avg(datediff(checkout_time, checkin_time)) from servicestable11'''
df=pd.read_sql_query(query,engine)
df
query='''SELECT AVG(Customer_Feedback) FROM servicestable11'''
df=pd.read_sql_query(query,engine)
df
query='''select count(servies_type) from servicestable11 where servies_type="Free Service"'''
df=pd.read_sql_query(query,engine)
df
query='''select car_number, Mileage from servicestable11 having max(Mileage)'''
df=pd.read_sql_query(query,engine)
df
query='''select car_number, Manufacture_year from servicestable11 having min(Manufacture_year)'''
df=pd.read_sql_query(query,engine)
df
CREATE TABLE customer_feedback ( Feedback int(11) NOT NULL, services varchar(50) NOT NULL, PRIMARY KEY (Feedback) )






