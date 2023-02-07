# PYTHON PROJECT SUPER CASHIER
### Nur Alam Saputra / nuralamsaputraa@gmail.com

# PROJECT BACKGROUNDS
A Friend need your help to create cashier program with some feature

# FEATURE REQUIREMENTS
1. Customers must be able to add or update items
2. Customers must be able to erase 1 items on the list
3. Customers must be able to reset their transaction
4. Customers must be able to see total transaction before proceed to pay
5. Customers get the "order's confirmed" when the input is right
6. Customers get the "error message" when there's error on the input
7. Discount applied when certain amount of total is achieved

# FLOWCHART
![Flowchart](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/flowchart%20super%20cashier.drawio.png)

# MODULES EXPLANATION

### 1. PrettyTable
![PrettyTable](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/01.%20prettytable.png)

Using library pretty table to create table for check order function
### 2. Class Transaction
![Transaction](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/02.%20class%20Transaction.png)

Create class transaction with atribute self.order to put the items in list
### 3. Add Item
![Add Item](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/03.%20add_item.png)

Add item with parameters item name, item quantity and item price in dictionary per item and append the next item into the list
### 4. Update Item Name
![Update Item Name](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/04.%20update_item_name.png)

Change certain item name in the list, with found list as the filtered item 
### 5. Update Item Quantity
![Update Item Quantity](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/05.update_item_qty.png)

Change certain item quantity in the list, with found list as the filtered item
### 6. Update Item Price
![Update Item Price](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/06.update_item_price.png)

Change certain item price in the list, with found list as the filtered item
### 7. Delete Item
![Delete Item](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/07.delete_item.png)

Delete certain item in the list, with found list as the filterd item
### 9. Reset Transaction
![Reset Transaction](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/08.reset_item.png)

Reset the transaction list and start anew
### 10. Check Order
![Check Order](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/09.%20check_order.png)

Check the transaction list in form of table using pretty table library, consist of item name, item quantity, item price and price total of item
### 11. Print Total
![Print Total](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/10.%20print_total.png)

Show how much amount customer need to pay, if certain amount is achieved customers will get discount.
# HOW TO USE 

### 1. Download cashier.py 
### 2. Make sure to install the requirement as listed in requirement.txt
### 3. Imported cashier.py module (make sure to put the module in the right directory)
### 4. Ready to use

# TEST CASE

### Following images is example of how i use the module using vscode

![Test Case](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/12.png)

![Test Case](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/13.png)

![Test Case](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/14.png)

![Test Case](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/15.png)

![Test Case](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/16.png)

![Test Case](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/17.png)

![Test Case](https://github.com/nuralamsaputra/Cashier-Project/blob/master/img/18.png)

# CONCLUSION

### I believe this python program will worked as intended and with comments and suggestion it will improve far better
