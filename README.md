# StocksApiWithViews (version 3)

#### In this version I have included UI to use the functionality of **SellOrder** and **BuyOrder**. 

## Overview

#### Basically, in this app the stock information of Microsoft Corporation and the company details are retrieved from API endpoint such as **Stock Price**, **Stock Symbol** and **Company Name**. The **Stock Price** is updated in every 3 seconds with the help of javascript code. To create a **New Order** we input shares quantity and select either Buy or Sell buttons. Buy button creates a Buy Order object, on the other hand Sell button creates a Sell Order object. The view of home page:
![image](https://user-images.githubusercontent.com/67966115/226131402-d46f1ebd-2ca8-466e-be79-29b315b8ae6f.png)



#### When buttons are clicked appropriately, the real-time data is submitted to the controller, after passing data validation through Model Binding they are proceded to create corresponding objects. In the **Order List** menu link '_GetAllBuyOrders()_' and '_GetAllSellOrders()_' are executed to retrieve the list of both Buy Orders and Sell Orders. The view of Order List.
![image](https://user-images.githubusercontent.com/67966115/226132651-2fa4cfe2-8021-47f4-9e9e-019b764e10da.png)


