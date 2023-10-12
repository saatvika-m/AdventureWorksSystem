# Adventure Works System
Problem statement:

Adventure Works Cycles wants a checkout system that enables users to edit and create orders. The users should be able to view and search for all the products. They also want a dashboard to view analytics of their products.

Proposed Solution:

I used Power Platform which is a low/no code platform used to build apps to design and build the app itself. I used Power Automate to create flows and Power BI to create the dashboard (All further explained down below).

Different Users:

 - Administrator - Admin team
 - Customer - Creates the orders
 - Line manager - Approves the orders

Functionality of the app:

I have linked videos which explain what the functionality of the app is. The product table contain all the data which was imported from an excel file. There are an additional two tables which are the Order table and the Shopping Basket table. The order table has all the details on the orders that the customer creates after they checkout. The Shopping Basket table includes the data of what is in the customers current shopping basket; they can edit this shopping basket in the app and remove and add items that they desire with the required quantity. 

After checking out, the line manager is sent an approval request via email using a Power Automate flow. After approval, the customer is then sent an email containing their order details. 

We used Power BI to create a dashboard which includes different statistical models to show analytics of the products. For example, it shows the most popular products. We creted this dashboard by using the information from the order table.
