This repo is for accepting payments from customers using PayPal.

This code is specific to Google Apps Script.

This solution uses both the client side PayPal Javascript SDK and the server side PayPal REST API to accept a payment from the buyer. 

This server code is specific to Apps Script, and the server call from the client side is also specific to Apps Script.

Much of the information needed is in the comments of the code.

NOTE: To go "live" you must:

Remove the word sandbox from the urls - See: https://developer.paypal.com/docs/paypal-plus/germany/integrate/test-and-go-live/#go-live
Use different client and secret credentials
