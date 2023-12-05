# Lab2_step1

Orders Table:  

id Integer Primary Key Auto Increment
address Varchar(50)
date Timestamp
status Integer
payMethod Integer
preferencesComment Text
location Decimal(2,7)

OrderProduct Table:

id Integer Primary Key Auto Increment
orderId Integer
productId Integer
amount Integer
