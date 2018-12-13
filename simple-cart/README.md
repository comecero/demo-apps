# Simple Cart
This is a very simple example that shows how to get a limited token for a new customer, get a list of products, add products to a cart and make a payment.

#### First Things First
Here's how to get started:
- [Create an account](https://signin.comecero.com/join/) with Comecero if you have not already done so.
- Within your account, go to Settings> Technical and enable "Allow Public Testing" (this allows anonymous to place test orders within your account)
- Get your account ID, if you don't already know it (look under your profile or go to Administration> Account Info)

#### Running the App
Open the file `simple-cart.html` and enter your account ID on line 11 of the source code. For example, if your account ID is AA0000, line 11 should look like this: `var account_id = "AA0000";`

_Chrome or Firefox_
If you are using Chrome or Firefox, you should be able to run the app from your local computer by double-clicking on the `simple-cart.html` page. That's it! No web server is required.

_Other browsers_
Other browsers may work with a simple double-click, but some browsers are limited in what they are able to do with pages that are launched over a local `file://` URL schema. If you would like to test another browser, you may need to access it over a web server.