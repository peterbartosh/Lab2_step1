# Lab2_step1

Orders Table:  

id Integer Primary Key Auto Increment  
date_and_time Timestamp  
status Integer  
preferencesComment Text  
location Decimal(2,7)  

OrderProduct Table:  

id Integer Primary Key Auto Increment  
orderId Integer  
productName Text,
amount Integer  
