# C-Programs

Collection of projects in C

Pop machine: A program which simulates the operation of a soft drink vending machine. 

Maintence requirements:
*	selling price in cents (range 30 cents to $1.05) from a command line argument (Assume valid integer on command line.)
*	provide a specific message for the following error cases and return to the operating system:
    * command line argument is missing
    * prices out of range
    * price not a multiple of 5 
*	with a valid selling price, put machine in-service for continual sales
*	as a maintenance action (hidden from menu), allow service person to shutdown (exit) the program altogether at the coin prompt by pressing E or e; refund any pending amount

Customer Requirements: 
*	There is only one flavour of pop, and that the machine won't run out of pop (no need to track inventory or total sales)
*	Display a welcome message stating the pop price, and what coins and commands are accepted
*	prompt the user to insert coins (via keyboard entry)
	accept a nickel [N or n], dime [D or d] or quarter [Q or q]; reject all other input except maintenance actions, then re-prompt for coin
*	after each coin, display how much the user has inserted in total and how much more the user needs to insert
*	dispense product on collecting sufficient money (only one flavour)
*	provide change for overpayment using only dimes and nickels (assume machine won't run out)
*	allow user to abort the transaction by pressing coin return (R or r). Refund using only dimes and nickels using the fewest number of coins. 
*	re-display selling price before new sale
*	continually prompt for additional sales -- do not exit the program

 
