# ETG-JSON-Based-Inventory-management-Assignment
# ETG-JSON-Based-Inventory-management-Assignment


This is an json based inventory management system built using python(json) and created on google colab.
I have developed this project as a part of hands on project which i recieved due to my "Skill India Python for ML/AI" Internship from #EliteTechnoGroups.

Thank you [Elite Techno Groups](https://www.elitetechnogroups.com/) for this internship opportunity and looking to learn more such knowledgeable stuff from you and the internship Guides.
Thank you [Ashish Jangra](https://github.com/AshishJangra27/) (Mentor) for helping me make this project from scratch.

-----
## About the Repository

### Problem statement

The issue offered was to build up an application which read the json document and show the data accessible.
After that the program should to create a invoice for a customer or consumer, with each purchase of the given item.
Likewise, after each purchase of some products the stock should be refreshed in same text file.

### Solution proposed

### I've made an Inventory Management System which is working on NoSQL based Database.
Inventory Management System Assignment we are supposed to convert dictionary data into json format using json module in python.
1. I've used JSON file System for it.
2. New Inventory can be added.
3. Purchase can be done.

### Features
1. Importing library for easy use
2. Then saving 30 items' details in dictionary type
3. Writing & Reading data of JSON file
4. Adding + Deleting + Purchasing Items
5. Loop is used to know whether the customer wants to buy more items or not
6. Total Cost of the item's or Billing Amount is calculated

#### I've added following features per product
- Product ID
- Name of Product
- Price
- Quantity
- Time is shown at the billing time

#### My Project can do the following things
1. Generate Bills
2. Update Inventory
3. Purchase for Customers
4. Add Items to Inventory

## Files Description
### Add_products_IMS.ipynb : 
file is used by admin to add products in inventory using python program in which one unique id called as product id is signed to every 
product which is used to access all atribute of product for updating values
### Purchase.ipynb :
it is python program used to Purchase product from inventory in which you can buy products and get bill after that the inventory is updated and sales are recorded in sales.json file
### record.json : 
it is inventory record file which contain products details and after every transaction it gets updated
### sales.json : 
it is record file of sales made in day which is updated after every transaction complition.

## About JSON:

JSON (JavaScript Object Notation) is an open standard record configuration and information trade design that utilizes intelligible text to store and communicate information objects comprising of characteristic worth combines and exhibits (or other serializable qualities). It is a typical information design with an assorted scope of usefulness in information exchange including correspondence of web applications with workers.
JSON is a language-autonomous information design. It was gotten from JavaScript, however numerous cutting edge programming dialects incorporate code to produce and parse JSON-design information. JSON filenames utilize the .json extension.

Firstly, we can take the data from input and give it to the dictionary, in my case it is named as resource.

Secondly, we import json and then we try to dump it into the json format,
if the file already does not exist it creates a file and fill it in with the data.
But, here the .json file contains data in str format.

We can also convert this .json file into dictionary format again using load.
