# Call-REST-in-CSharp
Step by Step on how to call REST in C# 

If you are wirting code everyday there is a hight chance that you need to use get or sent some information from one application to another and this means you need to call the api 
Here I've made a simple example on how to call Rest on your application in C# 


Application form ask you to enter your API request URI and it return the json response from the API 



EX: 
use this URI as request API URI 
https://api.coindesk.com/v1/bpi/currentprice.json 

In response you get something similar to this in the reponse form textBox : 

{"time":{"updated":"May 20, 2021 09:18:00 UTC","updatedISO":"2021-05-20T09:18:00+00:00","updateduk":"May 20, 2021 at 10:18 BST"},"disclaimer":"This data was produced from the CoinDesk Bitcoin Price Index (USD). Non-USD currency data converted using hourly conversion rate from openexchangerates.org","chartName":"Bitcoin","bpi":{"USD":{"code":"USD","symbol":"&#36;","rate":"39,492.9134","description":"United States Dollar","rate_float":39492.9134},"GBP":{"code":"GBP","symbol":"&pound;","rate":"27,986.3766","description":"British Pound Sterling","rate_float":27986.3766},"EUR":{"code":"EUR","symbol":"&euro;","rate":"32,402.1187","description":"Euro","rate_float":32402.1187}}}


