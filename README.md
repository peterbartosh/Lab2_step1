# Lab2_step1

Schema:

Orders Table:  

  date Date  
  status Integer  
  preferencesComment Text  
  lattitude Decimal(2,7)  
  longtitude Decimal(2,7) 
  id Integer Primary Key Auto Increment  


OrdersProducts Table:  

  productName Text
  amount Integer  
  id Integer Primary Key Auto Increment  
  orderId Integer
  FOREIGN KEY(orderId) REFERENCES Orders(id)
