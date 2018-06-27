# pub

The code in the class "Pub" violates a lot of clean code principles.  Refactor the code using TDD and Clean Code principles so that it
is more extensible and easy to use.

The requirements of a Pub are:

1) Can process a drink order from a customer and return a price.  A drink order contains an unlimited amount of drinks and a customer.
2) Types of customers are "General" and "Student".  Students get a 10% discount.
3) The drinks available are Corona for $6 (Beer), Budweiser for $5 (Beer), Miller for $5 (Beer), Red Wine for $7, White Wine for $8, Rum and Coke for $9 and Gin and Tonic for $10.
4) Only mixed drinks (Rum and Coke and Gin and Tonic) contain separate ingredients.  The Pub should be able to take an ingredient as a parameter and return the drinks that have that ingredient.

Bonus points:

1) Pub can calculate calories for a drink order.  Use Google to get a calorie count for each type of drink.
2) Customers can now order food in an order.  How would that impact existing design?  Refactor an order to allow food.
