# Block 18 Workshop: Writing Test Specifications

## Unit Testing

 - For the prompt "A function called multiplication that returns the product of the two input numbers."

* Expect multiplication(9, 2) to be a function
* Expect multiplication(9, 3) to be a number
* Expect multiplication(9, 3) to be eqaul to 27
* Expect multiplication(5, 2) to be eqaul to 10
* Expect multiplication(-5, 4) to be eqaul to -20
* Expect multiplication(-5, -5) to be eqaul to 25
* Expect multiplication("b", 3) to be an error

```
For the prompt "A function called concatOdds takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays."
```
* Expect concatOdds([2, 4, 7], [1]) to be a function
* Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be an array
* Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be eqaul to [-1, 1, 3, 9, 15]
* Expect concatOdds([3, 2, 2, 1], [7, 9, 13, 11, 14, 16]) to be eqaul to [1, 3, 7, 9, 11, 13]
* Expect concatOdds([3, 3, 2], [3, 3, 3, 3, 3, 3, 2]) to be eqaul to [3]
* Expect concatOdds([2, 2, 2], [4, 6, 8]) to be eqaul to []
* Expect concatOdds(["a", 6, 7], ["b", 9, 0, 0]) to be to be an error


## Functional Tests
```
For the prompt "A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest."
```
* When a user clicks on the “shopping cart” icon in the top right corner of the shopping site, they should be directed to a page that displays shopping cart being empty.
* When a user clicks the “Continue to Payment” icon, a pop-up should display the message “Your Cart is Empty.”
* When a user clicks on the search engine at the top of the page, they can type in any product they wish to purchase.
* When a user clicks the “Search” icon after inputting an item to search for, they should see the images and names of the items related to their search for “Legos.”
* When a user clicks on an item of "Legos" that they are interested in, they will see the full details. 
* When a user clicks on the "add to cart" icon, that "Lego" product should go into the shopping cart. 
* When a user clicks on the “shopping cart” icon in the top right corner of the shopping site, they should be directed to a page that displays the content of the shopping cart, including that "Lego" item that was added recently.
* When a user clicks the “Continue to Payment” icon, they should be directed to a page that displays a form for payment and shipping address. 
* When a user clicks the “Confirm Payment” button without filling in any payment information, a pop-up should display the message “Please fill in your payment information.” 
* When a user clicks the “Ok” button on the pop-up message, they should be redirected to a page displaying a form for payment and shipping addresses.
* When a user clicks on the payment form, they enter their payment information.
* When a user clicks the “Confirm Payment” button without filling in any shipping address information, a pop-up should display the message “Please fill in your shipping address information.” 
* When a user clicks the “Ok” button on the pop-up message, they should be redirected to a page displaying a form for payment and shipping addresses.
* When a user clicks on the shipping address form, they enter their shipping address information.
* When a user clicks the “Confirm Payment” button, a pop-up message will ask "Do you have an account with us".
* When a user clicks on the "No" button, anohter pop-up message will ask "Do you want to create one?"
* When a user clicks the “No” button, they should be redirected to a page that displays a message saying, “Your order is complete” along with the order ID, shipping number, and estimated date of delivery.
* When a user clicks on the "Home Page" icon, they should be directed to a main home page of the retial website. 
* When a user clicks on the search engine at the top of the page, they can type in any product they wish to purchase.
* When a user clicks the “Search” icon after entering an item to search for, they should see the images and names of the items related to their search input, specifically “iPhone Cases”.
* When a user clicks on an item of "iPhone Cases" that they are interested in, they will see the full details. 
* When a user clicks on the "add to cart" icon, that "iPhone Cases" product should go into the shopping cart. 
* When a user clicks on the “shopping cart” icon in the top right corner of the shopping site, they should be directed to a page that displays the content of the shopping cart, including that "iPhone Cases" item that was added recently.
* When a user clicks the “Continue to Payment” icon, they should be directed to a page that displays a form for payment and shipping address. 
* When a user clicks the “Confirm Payment” button without filling in any payment information, a pop-up should display the message “Please fill in your payment information.” 
* When a user clicks the “Ok” button on the pop-up message, they should be redirected to a page displaying a form for payment and shipping addresses.
* When a user clicks on the payment form button without filling in any shipping address information, they enter their payment information.
* When a user clicks the “Confirm Payment” button, a pop-up should display the message “Please fill in your shipping address information.” 
* When a user clicks the “Ok” button on the pop-up message, they should be redirected to a page displaying a form for payment and shipping addresses.
* When a user clicks on the shipping address form, they enter their shipping address information.
* When a user clicks the “Confirm Payment” button, a pop-up message will ask "Do you have an account with us?"
* When a user clicks the “No” button, a pop-up message will ask "Do you wan't to create one?"
* When a user clock the "Yes" button, a pop-up form should appear asking them to fill in their name, date of birth, and create a password.
* When a user clicks the “Create Account” button without filling in any information, an error message should indicate that they need to provide their name, date of birth, and create a password. 
* When a user clicks the “Create Account” button after filling in their name, date of birth, and password in the form, they should be directed to a page confirming their account creation with authentication. 
* When a user clicks the "Continue" button, they should be redirected to a page that displays a message saying, “Your order is complete” along with the order ID, shipping number, and estimated date of delivery.
* When a user clicks on the "Home Page" icon, they should be directed to a main home page of the retial website. 
* When a user clicks on the “Profile” icon, they should see a drop-down menu displaying the following icons: “Account,” “Settings,” and “Log Out.” 
* When a user clicks the “Log Out” icon, they are taken to the main home page of the retail website without being logged into their account.
* When a user clicks on the search engine at the top of the page, they can type in any product they wish to purchase.
* When a user clicks the “Search” icon after entering an item to search for, they should see the images and names of the items related to their search input, specifically “Action Figures”.
* When a user clicks on an item of "Action Figures" that they are interested in, they will see the full details. 
* When a user clicks on the "add to cart" icon, that "Action Figures" product should go into the shopping cart. 
* When a user clicks on the “shopping cart” icon in the top right corner of the shopping site, they should be directed to a page that displays the content of the shopping cart, including that "Action Figures" item that was added recently.
* When a user clicks the “Continue to Payment” icon, they should be directed to a page that displays a form for payment and shipping address. 
* When a user clicks the “Confirm Payment” button without filling in any payment information, a pop-up should display the message “Please fill in your payment information.” 
* When a user clicks the “Ok” button on the pop-up message, they should be redirected to a page displaying a form for payment and shipping addresses.
* When a user clicks on the payment form button without filling in their payment information, they enter their payment information.
* When a user clicks the “Confirm Payment” button without filling in their shipping address, a pop-up should display the message “Please fill in your shipping address information.” 
* When a user clicks the “Ok” button on the pop-up message, they should be redirected to a page displaying a form for payment and shipping addresses.
* When a user clicks on the shipping address form, they enter their shipping address information.
* When a user clicks the “Confirm Payment” button, a pop-up message will ask "Do you have an account with us".
* When a user clicks the “Yes” button, a pop-up form should appear, asking them to fill in their existing email and password.
* When a user clicks the “Login” button without providing both their email and password, a pop-up message will display “Please fill in your email and passcode.” 
* When a user clicks the “Login” button with providing their email and not password, a pop-up message will display “Please put in your passcode.” 
* When a user clicks the “Login” button after providing both their email and password, they should be directed to a page confirming they are officially logged in.
* When a user clicks the "Continue" button, they should be redirected to a page that displays a message saying, “Your order is complete” along with the order ID, shipping number, and estimated date of delivery.
