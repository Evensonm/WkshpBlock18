# WkshpBlock1

Unit Tests:
1. A function called "multiplication" that returns the product of the two input numbers.

    When a user inputs 2 numbers the function "multiplication" should multiply those 2 numbers together and return the product as the output

When a user in puts (7,3) the output should equal 21.
When only 1 number is inputed and error is returned.
When more than 2 numbers are inputed an error is returned.
When an input other than a number is submitted an error is returned.
When no input is submitted an error is returned.


2. A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.

    When a user inputs 2 arrays of integers the function "concatOdds" should cycle though the first array, find all the odd numbers, and put them in a new array. It then should do that with the second array putting the odd numbers in the same new array.  Finally, it should reorder the new array in ascending order. 

When a user inputs ([2,5,7], [-1,5,4,-3]) the function returns [-3,-1,5,7]
When a user inputs less than 2 arrays an error is returned.
When a user inputs more than 2 arrays an error is returned.
When an array has some values that are not numbers those values are ignored.
When one of the arrays has all values that are not numbers an error is returned.
When multiples of the same number are given that number is only returned once in the new array.


Functional Tests:
1. A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.

    When a user selects items from the website, those items are added to their shopping cart.  They then select the function "checkout" and are prompted to login or continue as guest.  The total for their cart is added, and the user is asked to add their payment method (ie credit card). After successful payment the user is shown a success screen and emailed a reciept.  The items from the cart are then forwarded to an external system to process for shipping.

When a user selects an item to purchase the item is added to the cart.
When a user wants multiples of an item they select the number from a drop down menu, and that quantity is added to the cart.
When a user does not select "add to cart" that item is not added to the cart.
When an item is out of stock the user is notified and the item is not put in the cart.
When a user clicks on "checkout" they are prompted to enter a username and PW to login or can continue as guest.
If the user does not enter information and clicks to login and error is returned.
If a user enters invalid information and clicks login an error is returned.
When a user successfully logs in or continues as guest they are shown the items in the cart and total.
The user may remove items at the checkout screen. The total is then updated.
When a user confirms the items and total they are prompted for payment information.
If payment information is invalid an error is returned.
When payment is successful the user is shown a success screen.
When payment is successful the user is emailed a reciept.
The order is forwarded to an external system for process in shipping.



