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

![A0BC7695-0E07-4AFA-B31F-D80155AA6CB7](https://github.com/saatvika-m/AdventureWorksSystem/assets/145695375/188664d7-a3e9-4fd4-9a86-d2d0c11c754a)

![6D99A89B-D4EB-411A-883E-436460C94A42](https://github.com/saatvika-m/AdventureWorksSystem/assets/145695375/5ffc0638-4252-43ae-8516-dbf695db547a)
![5C07BB05-7196-4EA0-8F15-6720D3E3850C](https://github.com/saatvika-m/AdventureWorksSystem/assets/145695375/d5173858-58b3-4604-b528-478977beb43d)
![DB24DB4C-2807-4CE0-BA97-88F53DBCDC60](https://github.com/saatvika-m/AdventureWorksSystem/assets/145695375/dcc26382-bbb2-41ea-ba50-1334e5383fbb)

After checking out, the line manager is sent an approval request via email using a Power Automate flow. After approval, the customer is then sent an email containing their order details. 

![0B9CC5A1-8028-4840-9DF1-F7F3ED2514FC](https://github.com/saatvika-m/AdventureWorksSystem/assets/145695375/e7d2233e-801c-4a01-8a83-4bf13969709f)
![D6F60300-86E4-42B5-BDAF-876932F62697](https://github.com/saatvika-m/AdventureWorksSystem/assets/145695375/57312262-e624-4699-8380-c00c47222e40)

We used Power BI to create a dashboard which includes different statistical models to show analytics of the products. For example, it shows the most popular products. We creted this dashboard by using the information from the order table.

![44FC1B53-C69B-4A45-B04C-1BEA88182CF8](https://github.com/saatvika-m/AdventureWorksSystem/assets/145695375/0a875c72-8526-4c12-b5d1-e49679d7bc28)

