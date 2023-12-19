## => This project is to analyze the sales of a pizza restaurant,  extract key performance indicators, and find out the bestselling months and times.

## => Data (This data belongs to a pizza restaurant)

1)	order_id: Unique identifier for each order placed by a table

2)	order_details_id: Unique identifier for each pizza placed within each 

3)	order (pizzas of the same type and size are kept in the same row, and the quantity increases)


4)	pizza_id: Unique key identifier that ties the pizza ordered to its details, like size and price

5)	quantity: Quantity ordered for each pizza of the same type and size


6)	order_date: Date the order was placed (entered into the system prior to cooking & serving)

7)	order_time: Time the order was placed (entered into the system prior to cooking & serving)


8)	unit_price: Price of the pizza in USD

9)	total_price: unit_price * quantity

10)	pizza_size: Size of the pizza (Small, Medium, Large, X Large, or XX Large)


11)	pizza_type: Unique key identifier that ties the pizza ordered to its details, like size and price


12)	pizza_ingredients: ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they all include Tomato Sauce, unless another sauce is specified)


13)	pizza_name: Name of the pizza as shown in the menu



## => Questions
1.	what is total revenue ?
2.	How many orders were ordered during the year?
3.	How many pizzas were ordered during the year?
4.	what is the most pizza category were ordered ?
5.	what are sales and number of pizza were ordered each month ?
6.	what is the most month that has sales ?
7.	What is the best-selling time of the day?


## => Data Preparing
1)	We remove Order Time and make time by hour  for example if order time is 11:55:00 AM then order time is 11 (this mean is from 11 to 12) .

2)	We Can add Day Name Column that contains the name of day .


## => Insights
1)	Total Revenue over year = 817.9K $

2)	The number of Orders were ordered over year = 21.4K orders

3)	The number of Pizza were ordered over year = 49.6K pizzas

4)	The Average Revenue for month = 68.2K $ 

5)	The bestselling type of pizza is the classic pizza

6)	The best months are those that covered the average return of 68.2K $, but there are 4 months that did not cover 68.2K $: February, September, October, and December.

7)	The best month is July, whose revenue exceeded 72.5K $

8)	In most months, the best days for selling are Thursday, Friday, or both.

9)	The best-selling times are approximately every month from 12:00 PM to 3:00 PM, I think it is lunch time. From 4:00 PM to 9:00 PM, sales are also good, but less than the previous time.

10)	But before 12.00 PM there are no good sales because it is not almost lunch time, and the restaurant opens at 10.00 AM.

11)	After 9.00 PM there are no good sales either because we have passed dinner time
