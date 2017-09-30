# INVENTORY MANAGEMENT 


Confidential Information Notice. 

Copyright 2017. All Rights Reserved. Any unauthorized reproduction of this document is prohibited. 

This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.

-------------

## INTRODUCTION

Having an **Inventory Management** solution is a must-have for retail businesses that want to be more efficient and keep data accurate. If your inventory is not enough to supply, you may lose customer. But if the inventory you keep is more than needed, it will cost you lots of money to manage. Thus, it is vital to equip your business with an effective inventory system to always keep your warehouses at an ideal stock level. Magestore team has been working hard to offer you a friendly & affordable stock management solution for Magento 2 with smart design, clean and simple workflow to handle every activity about stock management, stock transfer, stock taking and low stock notification... in your warehouses in the most efficient way.  Moreover, this guide is specially written by  business flow which divided into processes so you can quickly access to the part you need.

With the latest upgraded version and its convenience and the amount of time saved, we hope that you would enjoy and feel exhilarated when experience this newest ones. 

Thanks and Best regards,

**Magestore Team** 
-----------

## WORKFLOW
### Inventory Adjustment 
![](./image_Inventory%20Management/image001.png?raw=true)

### Transfer Stock - Send Stock

Anh2 ![enter image description here]()

### Transfer Stock - Request Stock

Anh 3 ![enter image description here]()
### Good Receipt
Anh 4 ![enter image description here]()
### Good Delivery
Anh 5 ![enter image description here]()
### Drop Shipping
Anh 6 ![enter image description here]()


----------


## PERMISSION MATRIX
anh 7 ![enter image description here]() 


----------


## HOW TO USE 
### Inventory Adjustment
- *Path: Inventory Management > Stock Control > New Stocktaking*

There are two stages in an inventory adjustment process: **Stocktaking and Stock Adjustment**. Stock-taking or "inventory checking" is the physical verification of the quantities and condition of items held in an inventory or warehouse. This may be done to provide an audit of existing stock. It is also the source of stock discrepancy information. 

To begin, inventory excutive staff will count every items in the inventory location, then check the physical count against the system records. If there are any discrepancies, inventory excutive staff have to make a note about variances and follow up where necessary. Once the stock take has been finalized, update the inventory records in the module inventory adjustment.

The process is divided into these steps below: 

➢	**Step 1:** *Inventory Manager creates Stock Taking then exports list of product*

Anh 8 ![enter image description here]()

1.	Select the warehouse to do the stocktaking.
2.	You can customize the stocktaking code (in fact, this data is auto generated by the system).
3.	Enter names of people who participate in this stocktaking process.
4.	Select stocktaking time
5.	Enter the reason why you do this stocktaking.
6.	Click on “**Prepare Product List**” to select products.

Anh 9 ![enter image description here]()

*On the pop-up screen:*
There are 2 ways to prepare a product list:
7.	Click on “**Add Products to stocktake**” to select products. 
8.	Or Click on “**Import Products**” to import a products list from your device.
9.	Click on “**Start Stocktake**” to activate the process.

➢	**Step 2**: *Inventory Staff counts quantity of product in stock -> Update Stock Taking (input data)*

anh 10 ![enter image description here]()

10.	Enter the amount of items physically counted
11.	Click on “**Complete Data Entry**” 

anh 11 ![enter image description here]()

12.	Click on “**Re-data Entry**” to re-select the product list (if any).
13.	Click on “**Complete Stocktake**” to fulfil the stocktaking process.
14.	Click on “**Export Counted Products**” to transfer the data of physical counted products to an excel file (optional).

➢	**Step 3**: *Inventory Manager creates Adjust Stock -> Complete Adjust Stock -> Update the inventory records* 

anh 12 ![enter image description here]()

15.	Click on “**Adjust Stock**” to update the inventory records 
16.	Click on “**Export Difference List**” to transfer the data of discrepancies into an excel file (optional)

Anh 13 ![enter image description here]() 

*On the pop-up screen:*
17.	Enter the adjust quantity
18.	Click on **Adjust** to update the inventory records

Anh 14 ![enter image description here]()

*On the pop-up screen:*
This final pop-up screen summarises the data of your recently inventory adjustment, including: old quantity, change quantity (discrepancies) and adjust quantity. 
19.	Click on **Export Products** to transfer the data to an excel file on your device.


### Transfer Stock - Send Stock
- *Path: Inventory Management > Transfer Stock > Send Stock* 

When admin wants to send stock from his warehouse to another warehouse, the process to Send stock is included: 

- **Step 1**: *Delivery warehouse Manager creates Send Stock*
- **Step 2**: *Staff at Delivery warehouse picks/packs stock at warehouse -> Send Stock* 
- **Step 3**: *Staff at Receipt warehouse checks quality -> confirms quality to Manager*   
	-  Good quality -> Receive Stock -> Save Receive Stock -> Mark as Completed. Now you can download Shortfall list & Summary of the Send Stock.
	-  Not meet enough quality -> Return Stock  -> Complete Transfer Stock

➢	**Step 1 + 2**: 
anh 15 ![enter image description here]()

Fill the **Transfer Code**, choose **Source Warehouse** and **Destination Warehouse**
Fill in the **Reason** box

anh 16 ![enter image description here]()

To prepare product list, click on the **Prepare Product List** button

anh 17 ![enter image description here]()

Add new list (click on **Select Products**) or import a list of product prepared before (click on **Import**)

anh 18 ![enter image description here]()

To add new list of products, 
1. Click on the product needed 
2. **Add Selected Products**

Anh 19 ![enter image description here]()

3. Choose the quantity to transfer and click on **Start Send Stock**
4. Click on **Remove** to delete product line

Anh 20 ![enter image description here]()

The send transfer is completed

➢ **Step 3**:

Anh 21 ![enter image description here]()

1. Click on the send created for receiving
2. Click on **Add Selected Products**

Anh 22 ![enter image description here]()

Write the quantity received in receiving history 

Ahn 23 ![enter image description here]()

Click on **Save Receive**

Anh 24 ![enter image description here]()

Anh 25 ![enter image description here]()

Create receiving successfully

### Transfer Stock - Request Stock

- *Path: Inventory Management > Transfer Stock > Request Stock*

If a warehouse lacks of stock, admin can create a Stock request to get stock from other warehouse. The process to request stock includes:

 - **Step 1**: *Receipt warehouse Manager creates request*  
 - **Step 2**: *Delivery warehouse Manager checks, then Staff picks/packs stock at warehouse -> Send Stock* 
 - **Step 3**: *Staff at Receipt warehouse checks quality*
   + Good quality -> Receive Stock ->Save Delivery Stock -> Save Receive Stock -> Mark as Completed. Now you can download Shortfall list & Summary of the Request Stock.
   + Not meet enough quality -> Return Stock  -> Complete Transfer Stock

**Step 1+2:**


Anh 26 ![enter image description here]()

Fill the **Transfer Code,** choose **Source Warehouse** and **Destination Warehouse**
Fill in the **Reason** box

Anh 27 ![enter image description here]()

To prepare product list, click on the **Prepare Product List** button

Anh 28 ![enter image description here]()

Add new list (click on **Select Products**) or import a list of product prepared before ( click on **Import**)

Anh 29 ![enter image description here]()

To add new list of products, 
1. Click on the product needed 
2. **Add Selected Products**

Anh 30 ![enter image description here]()

3. Choose the quantity to transfer and click on **Start Request Stock**
4. Click on **Remove** to delete product line

Anh 31 ![enter image description here]()

The request transfer is completed

**Step 3**: 

 - **DELIVERY STOCK**

Anh 32 ![enter image description here]()

Click on **Select Products** in delivery history

Anh 33 ![enter image description here]()

1. Click on the request created for the transfer
2. **Add Selected Products**

Anh 34 ![enter image description here]()

Write the quantity deliveried in delivery history

Anh 35  ![enter image description here]()

Click on **Save Delivery**

Anh 36 ![enter image description here]()

Create delivery sucessfully

 - **RECEIVE STOCK**

Anh 37 ![enter image description here]()

Click on **Select Products** in receiving history

ANH 38  ![enter image description here]()

1. Click on the request created for receiving
2. Click on **Add Selected Products**

Anh 39 ![enter image description here]()

Click on **Save Receive**

Anh 40 ![enter image description here]()
Anh 41![enter image description here]()
Create receiving successfully.

### Goods Receipt from Customer Return

The following goods receipt workflow only applies for refund sales order requested from customers. The return goods will be confirmed by sales staff before getting restored back to any selected warehouse. 

 - *Path: **Sales > Order**  > Select Refund Order(s) requested > Credit Memos*

Now let’s go to the detailed steps: 

#### Check order information

 - First, Go to **Sales > Order** > Select to the refund order requested
   from customer.

Anh 42 ![enter image description here]()

 - If the order was invoiced and shipped to the customers, the refund request will be accepted. Then go to the next step.  
 If the order didn’t meet the refund policy (exceed a certain time limit etc), then the staff can end the refund process and complete the order without further adjustment.

####    Check goods condition/quality 

After checking the refund condition regarding the requested refund order, sale staffs also have a duty of checking goods condition/quality before accepting the refund request from customer. 

#### Implement the refund process in the system 

When the refund order is accepted, follow this step to complete the refund process: 

 - **Step 1**:  Go to Sales > Order > Create Credit Memo

Anh 43 ![]()

 - **Step 2:** 
   1. Select Warehouse where refund goods will be restored. 
   2. Input the quality to refund.

Anh 44 ![]()

 - **Step 3**: End the refund offline process.

Anh 45 ![]()

### Goods Delivery
#### Create New Order 

-	*Path: Fulfillment > Order Listing > All orders*  

-  *Or Sales > Orders*

Anh 46 ![]() 

 1. Click on **Create New Order**
    
 Anh 47 ![]()
    
 2.  Double click on a customer line to select a customer  
    
 Anh 48 ![]()
 3. Click on **Add Products** 
 Anh 49 ![]()
 4. Click on **Search** and use filter to search expected products 
 5. Mark the checkbox to **select products** 
 6. Enter the **quantity** to order
 7. Click on **Add Selected Products** to order 

Anh 50 ![]()
8. Mark the checkbox **Custom Price** to customize a price 
9. Mark the checkbox to **Apply discount** (if any)
10. **Apply coupon code** and **Use gift card to checkout** 

Anh 51 ![]()
11. Select a **shipping method**

Anh 52 ![]()
12. Mark the checkbox to **append comments** or **email order confirmation** to the customer
13. Click on **Submit Order.**

The order has been created successfully.

#### Verify Orders


 - *Path: Fulfillment > Order Fulfillment > Verify Orders*

Anh 53 ![]()

1. Click on **Process Verify** to verify the order

Anh 54 ![]()

2. Click on **Mark as Verified**, then the order has been verified successfully

#### Prepare Fulfil

Anh 55 ![]()

1. Click on tab **Prepare Fulfill** on the top sidebar
2. Click on Fulfill

Anh 56 ![]()

*On the pop-up screen*
3. Select a **shipping channel** on the dropdown list 
4. Click on **Add products** to request

Anh 57 ![]()
5. Mark the checkbox to **select products**
6. Enter the **quantities to pick**
7. Click on **Add Selected Products** to request

#### Pick Items
Anh 58 ![]()