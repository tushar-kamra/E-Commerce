# E-commerce Web App 
> ## Theme: Atmanirbhar Bharat

Live at: http://tusharkamra.epizy.com/atmanirbhar






## Introduction

In the current era, almost every business has been revolutionized with digitalization, 
and E-commerce has shown tremendous growth in the retail sector. Across the globe, 
businesses are getting online and entities like Traders, Suppliers, Wholesalers, Buyers, etc 
are effectively managing the Supply Chain Management(SCM). Since buyers are being provided 
with a wide range of products from different retailers across the globe, there are many retailers 
from our own country like local vendors, sellers, and service providers such as domestic manufacturers, 
small business owners, women entrepreneurs, and Self-Help Groups which are not getting enough recognition 
which in turn affects the productivity and supply chain of the country. To support our country's 
retailer, a separate web app is needed to provide recognition to local retailers, thus "Vocal for Local". 

This web app consists of two portals, viz. Vendor and Customer. 
## Vendor Portal (vendor.php)
The vendor portal consists of a Signup and a Login page. Anyone doing business in any location in the country 
can get themselves registered on the platform and can directly sell their products such as a table, chair, fan, 
air conditioner, carpet, and similar such articles or services of common use. After successful registration (log_vendor.php), 
vendors are required to log in and authenticated vendors (authenticate_vendor.php) are redirected to the 
dashboard (vendor_dashboard.php) thus allowing them to add/delete (add_item.php / delete_item.php) the products. 

## Customer Portal (customer.php)
The customer portal consists of a Signup and a Login page. Consumers can use this platform to purchase goods at 
the ease of sitting at their home. After successful registration (log_customer.php), customers are required to 
log in and authenticated users (authenticate_customer.php) are redirected to the dashboard (customer_dashboard.php) 
where they are provided with the list of products. Customers can select product from the list and the selected 
products will get added to the cart (add_cart.php). To place order (place_order.php), customer can click on the checkout button
and fill the required details to complete the transaction (log_order.php).

## Technical details
Front End: HTML5, CSS3, Bootstrap 4
Back End: PHP
Database: MySQL

## Database Structure
Database name: Atmanirbhar (populate using atmanirbhar.sql)
Relations:
1) customer - stores customer profile
2) vendor - stores vendor profile
3) catalog - stores product information provided by vendors
4) cart - stores active selection of products
5) orders - stores order history

## Additional Features
1) Feature of cart has been added to ease product selection process,
2) Vendor and Customer, both can view order history.

## Future Scope
1) Order tracking can be implemented,
2) Product return policy can be introduce in case of faulty product delivery.


--------------------------------------------------------------------
To run this web app on local machine, follow the underlying steps:
1) Install XAMPP (XAMPP is a free and open-source cross-platform web server solution stack package)
2) Open XAMPP Control Panel
3) Start Apache(Web Server) and MySQL
4) Populate database using atmanirbhar.sql
5) Run in the browser

Happy Coding !

![](https://github.com/tushar-kamra/E-Commerce/blob/master/ss.png)
