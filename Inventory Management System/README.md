# Inventory-Managment-System
Features of Inventory Managment System:
1)List of available items will be shown to user
2)User can purchase products by using product_id
3)User can purchase one or more products at a time
4)Bill will be genrated with timestamp and customer name
5)Show Bill with description 
6)Discount will be shown on bill(7% discount will be given to every customer) 
7)Amount payable before and after discount will be displayed on bill 
8)Records will be updated after every purchase 
9)Transaction will be stored in json file with timestamp
............................................................................................................................

IMS product_purchase.ipynb file:
<1>Used to genrate bill.
<2>Used to update records of Inventory in records.json file.
<3>Used to update transactions in sales.json file.

.............................................................................................................................

IMS Product Add.ipynb file:
<1>Used to add & update quantity of old products which are already in inventory.
<2>Used to add & update new products in inventory i.e. records.json file.
<3>Used to delete & update data from inventory i.e. records.json file.

............................................................................................................................

Records.json:
<1>All the records related to product are stored in this file
<2>'Product_Id': {'Product_Name': '',
  'Product_Company': '',
  'Quantity_Available': ,
  'Price( in RS.)': ,
  'Weight( in gms)':}
  
............................................................................................................................

sales.json:
<1>All transaction details are stored in this file.
<2> 'Transaction_Id': {'Time': ,
  'Product_Id': ,
  'Quantity': ,
  'Amount': }
