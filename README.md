# PowerBi_NorthwindDB
Exploring the Northwind database with Power Bi

Here I built a dashboard using the Microsoft Northwind Traders database as my first experience with Power Bi.
Previouly I had been using Metabase DB management and dashboard tools but I have discovered how much more effective 
Power Bi is in Database management and dashboard creation.

Initialy I used the data provided by my teacher at Spiced academy and constructed a DB in PostgreSQL but for this project 
I am using the data from the [services.odata.org](https://services.odata.org/Northwind/Northwind.svc/) website.
PowerBi offers a mutliple great features to get data from differnt sources, getting it directly online in a useable format is fantastic in my opinion.

In this first and simple dashboard I began by downloading Power Bi desktop. I normally run my laptop in Ubuntu but I still have Windows 10 installed and to save setting up a virtual machine and reinstalling Windows there, I switched over to Windows. Having not used it in 6 months it took some time for all the updates to finish and I could use Power Bi desktop without issue. 

Once everything was ready I went to the [services.odata.org](https://services.odata.org/Northwind/Northwind.svc/) website and copied the link and then using the get data button I inputed the website and connected to the data. I used a tutorial from [AnExcelExpert](https://www.youtube.com/watch?v=czON7fhEuYI&t=1599s&ab_channel=PK%3AAnExcelExpert) to build the background images in MS Powerpoint. If you are using this as an example to do your own, please feel free to use my images for your back ground. You can find them in the Background images folder.

After this i set about creating some useful indices such as Gross Revenue, Discount % and $ and also Net Revenue which is Gross rev - discount $, I also created other useful measures which you can see.


![Northwind_overview_page](https://user-images.githubusercontent.com/105222741/211288089-b40e26a1-beec-4dcc-80d9-bd1d2c472ef7.jpg)


I added drop down menus (slicer) to be able to select differnt product and categories, country and city and also employee. With these you can see many different options and find useful data visualisations based on specific requirements.

![Northwind_Category Products_page](https://user-images.githubusercontent.com/105222741/211288438-401ca72a-135d-40e9-b4b6-a7166e8554ad.jpg)

On the Category and products page, which is accessable via the button in the left column you can get detailed information about different cateorgies and products. Just use the drop down menus to go deeper into whatever feild you choose. 
For example you can select a specific category or product, then choose which country to see the breakdown of revenue and performance. 

## Business Analysis

With this information we can make informed decisions on where to focus increase marketing, or possibly offer more discount for higer product purchase volume.

![Northwind_Employees_page](https://user-images.githubusercontent.com/105222741/211289302-b1ef4ec1-0a7b-44c7-be6a-e8e3f3eab60e.jpg)

Here is the danger page for Employees
If we select the Sales representitves we can see who needs improve more and who is doing well

![Northwind_Employees_page_title](https://user-images.githubusercontent.com/105222741/211290920-31345afd-afca-459b-9b9f-804f3f1d1061.jpg)

Also upon quick analysis we can see a large overstock of Laughing Lumberjack Lager which should be put on discount and cleared and probably discontinued as Northwind had only 3 orders for this in 1996 and holding onto unnecessary stock is costing the company money both in storage space and wasted capital.
Chang beer is trading well but Northwind ahs not kept up with stock and the restock order has not been placed. 

![Northwind_Category Products_issues_page](https://user-images.githubusercontent.com/105222741/211295917-4556076c-07db-4dbe-bff3-5a8b1a21e9ad.jpg)




