To Enable Stripe payment on your site, please follow these steps below:

1\. Go to Dashboard &gt; Settings &gt; Payment settings &gt; Stripe Checkout &gt; Enable Stripe Checkout V2

2\. Input Secret Key + Publishable Key + Webhook Secret

*Some optional options: Custom Name / Description / Logo*

*+ Sandbox Mode is for testing*

![](/assets/images/stripe-payment/dd316a24ad6ee30c46886831e837956f.png)

##### 1. How to get Secret API key

To obtain your Stripe Secret Key, follow these steps below:

1\. You need to log in to your Stripe account.

2\. In the dashboard view, navigate to the left side menu,

first click on ‘Developers’ and select ‘API keys’. This will display a screen on the right-hand side.

3\. Under ‘Standard keys’, you will see ‘Secret key’ and a button named ‘Reveal live key’.

Click on the button and it will display the secret key.

Or read more here: <https://stripe.com/docs/keys>

![](/assets/images/stripe-payment/887fcfb8345d825cda43b01886b11858.png)

##### 2. Steps to receive webhooks 

1. Go to your Stripe log in &gt; Add a Webhook, input webhook link, ex: Webhook URL: [http://linkURL.com/gateway/gateway\_callback/stripe](http://dev.bookingcore.org/gateway/gateway_callback/stripe)
2. Then a secret key will be generated, Copy the Signing secret key and input it to Webhook secret key field in the Setting
 
![](/assets/images/stripe-payment/ce16c628f469a039a83086bbee85ea78.png)