# pub

The code in the class "Pub" violates a lot of clean code principles.  Refactor the code using TDD and Clean Code principles so that it
is more extensible and easy to use.

The requirements are:

1) Can process a drink order from a customer and return a price.  A drink order contains an unlimited amount of drinks and a customer.  The drinks available are Beer, Wine, and Mixed Drinks.
2) Types of customers are "Regular", "Senior" and "Student".  Students get a 10% discount.  Seniors get a 20% discount.
3) Drink prices are based on volume of the drink.  Every 12 oz of Beer costs $5.  5 oz of Wine costs $7.  1.5 ounces of liquor in a Mixed Drink costs $6.
4) Given all the orders for the day return the most popular drink.

Bonus points:

1) Calculate calories for a drink order.  Calories are also based on volume.  There are 12 calories in an oz of beer, 24 calories in an oz of wine, and 71 calories in an oz of liquor.
2) Customers can now order food in an order.  How would that impact existing design?
