# ChangeMakerApp
This simple Android application was inspired by an assignment for my CSC 110 class at Mesa Community College.

Imagine a vending machine that only accepts $1 bills as payment and all items in the machine are priced between $0.25 and $1.

Once the user inputs the price of their item (in cents) the app displays the change the user will receive and the denomination (in this case the type of coin- quarter, dime or nickel).

If the user inputs a price less than 0 cents or greater than the maximum price of $1 (100 cents), they will receive an error message.

Also, if the user inputs a price that is not a multiple of 5 cents, they will receive an error message.  This is because a constaint of the original assignment was that output could only be in quarters, dimes and nickels.
