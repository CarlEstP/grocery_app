## GROCERY APP

Based in a codebasics project
https://github.com/codebasics/python_projects_grocery_webapp/tree/main

## 1. Purpose of the Project

In this python project, we will build a grocery store management application. It will be 3 tier application,

- Frontend: UI is written in HTML/CSS/Javascript/Bootstrap
- Backend: Python and Flask
- Database: MySQL

![header_photo](https://github.com/CarlEstP/grocery_app/blob/main/img/manage_orders.PNG)

![header_photo](https://github.com/CarlEstP/grocery_app/blob/main/img/manage_products.PNG)

## 2. Stack

- Python
- Flask
- MySQL
- Javascript
- HTML & CSS & Boostrap

![header_photo](https://github.com/CarlEstP/grocery_app/blob/main/sql/gs_schema.PNG)

## 3. Cases of uses and funcionality

In this app you can do:

- See the list of products and manage them: insert, modify and delete
- See the list of orders and manage them

## 4. How to run the app

1. Set up your sql server. You can import de grocery_app.sql file
2. Edit the sql_conection.py file with your sql connection personal info
3. Run the server.py file in your terminal
4. Click on the index.html on your navigator

## 5. Tasks to implement

The grocery management system that we built is functional but have some issues and new features that should be implemented:

- Products Module: In products page that lists current products, add an edit button next to delete button that allows to edit current product

- Products Module: Implement a new form that allows you to add new UOM in the application. For example you want to add Cubic Meter as a new UOM as the grocery store decided to start selling wood as well. This requies changing backend (python server) and front end (UI) both.

- Orders Module: When you place an order it doesn't have any validation. For example one can enter an order with empty customer name. You need to add validation for customer name and invalid item name or not specifying a quantity etc. This is only front end UI work.

- Orders Module: In new order page there is a bug. When you manually change total price of an item it doesn't change the grand total. You need to fix this issue.

- Orders Module: In the grid where orders are listed, add a view button in the last column. On clicking this button it should show you order details where individual items in that order are listed along with their price/quantity etc.
