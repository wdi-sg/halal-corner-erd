# Asyraf’s Halal Corner - Entity Relationship Diagram (ERD) 

![https://media.giphy.com/media/SKqVXl0LKqJvq/giphy.gif](https://media.giphy.com/media/SKqVXl0LKqJvq/giphy.gif)

Asyraf has contracted developers to digitize workflows, streamline processes and enable data driven KPIs.

You are now the developer for their backend. We have written specifications for you.

Note: Not all of the required columns / data are explicitly listed as a specification.

* Think of tables
* Think of columns
* Think of relationships

### Basic Deliverables

We are implementing an self-checkout kiosk ordering system. (like at mc donalds) And a POS system that organizes the orders.

We want to enable Customers to be able to choose `Food Items` from The Menu, add to the `Cart`, which has many Food Items, then see the ones chosen, then checkout and `Pay`.

### How to Start

You will not be writing any javascript for this exercise, only SQL.

Work backwards by first imagining the pages that will display the data needed for each step of the user flow.

- User sees menu items
- User clicks to add to cart, sees items in cart
- User Checks out and pays
- Kitchen Staff sees order and fulfills it.

For each of these pages what kind of data is suggested that you store and display? (`SELECT` and `INSERT` queries)

On a piece of paper write the tables and columns and rows that you need.

On a piece of paper write the rows of data that would represent the queries that you make (`SELECT` and `INSERT` queries)

Write the actual SQL statments to create the tables, and then the `INSERT` queries needed to create rows in those tables.

Write the SQL to get the data back out for each page.

Some furthers ask for some analytical data. Make sure when coding through the process that you are capturing this data.

Do this for each further section below. Do the whole workflow for each further. Don't just write the ERD for all sections at once and go back to write SQL, etc.

#### further

There are Promotional Food Items that will appear on The Menu on Tuesday to Friday but disappear on Saturday to Monday.

#### further


At 6pm each day, the store has to be able to tell that their Ingredients are still sufficient for the food making until the next 6pm.

#### further
And we want to know when to order the ingredients again.

#### further

Write seed data and queries for:

- Number of Customers who like prata and ayam penyet
- Number of Customers who changed from always getting prata to getting ayam penyet
- Which is the most popular food?
- What are the rankings of the top 10 food?
- What is the profit for this month?

#### further

We want to show customers the amount of calories for each Food Item.

#### further


We buy Ingredients from many different Suppliers where some Suppliers sell us many different Ingredients and sometimes we switch to a cheaper Supplier to make more profit.

#### further

We want to find out the profit for the month.

We want to make sure that the store is able to make a profit and does not have any deficit for the sales in the month.

#### further

We want to be able to find out which Period has the most number of customers paying for our food.

#### further


We want to find out the most popular food.

#### further


We want to find out the ranking of the top 10 food.

#### further


We will have an advertisement for our secret recipie ayam penyet next week and we want to find out the increase in sales due to the advertisement.





#### further

We want Customers to be able to make Custom Orders for each Food Item - like extra sauce.

#### further

We want to find out whether the people who like extra sauce in their burger also like to buy large french fries.

#### further

We want to find out which Suppliers are repeatedly overcharging us.

#### further

We now have 5 outlets and we want to find out which outlet is the best one.
