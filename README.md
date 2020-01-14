# Virtual-restaurant-c-

The program simulates a restaurant management
system. The program will open the restaurant, assign customers to tables, make orders,
provide bills to the tables, and other requests.
The program will get a config file as an input, which includes all required information about the
restaurant opening - number of tables, number of available seats in each table, and details
about the dishes in the menu. The format of the input file is further described in part 3.5.
There are 4 types of customers in this restaurant, each customer type has its own way of
ordering from the menu (an ordering strategy). 
Each table in the restaurant has a limited amount of seats available (this info is provided in the
config file). The restaurant can’t connect tables together, nor accommodates more customers
than the number of seats available in a table. In this restaurant, it’s impossible to add new
customers to an open table, but it’s possible to move customers from one table to another.
A bill of a table is the total price of all dishes ordered for that table. 
The program receives the path of the config file as the first command line argument. Once the
program starts, it opens the restaurant by calling the start() function, followed by printing
“Restaurant is now open!” to the screen.
Then the program waits for the user to enter an action to execute. After each executed action,
the program waits for the next action in a loop. The program ends when the user enters the
action "closeall" .
