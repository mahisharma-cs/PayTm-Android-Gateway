# PayTm-Android-Gateway
Paytm Gateway for android application. Using volley library to fetch data from a webpage. Payment through paytm for any enterprise application.

# Test and Production Mode
Paytm provide two types of gateway. The test one and in production mode. This method which I am going to explain works in only production mode. I am using paytm gateway API for website. Then fetch data from website whether the transaction is done or not.

# We do not need extra activity
 - As we are done payment through paytm. It provides flexibility to complete the transction.
 - If paytm application is installed in user's device then the payment is provide good interface for complete checkout.
 - Else if the paytm application is not installed in user's device then the payment would complete through webpage.
 - Do not worry about payment... It is complete in any case.
 
# You just need to pass three parameters
# (orderid,transaction-amt,merchant-id)
 - Yes, you read correct. Only you need to pass these three parameters and get a transaction token of exact 45 characters.
