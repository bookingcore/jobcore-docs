- This method allows your user can book service, and they can pay immediately via Paypal account.
- To enable this method you just need to Enable Paypal
- Continue to enter your PayPal information.
 
![](/assets/images/paypal-payment/e5f1856e6b9ec14ffb8f3a8121b93891.png)

**2. Obtain PayPal API Credentials**

PayPal API credentials (Username, Password, and Signature) are necessary if you want to integrate your forms with PayPal Pro. These are separate details from your PayPal login information.

Note that PayPal Pro is available to Premium or Business type PayPal account. You may be able to view API credentials with your Personal account, but the integration will not work with it.

Here’s how to obtain Paypal API credentials for your account:

1\. Log in to [PayPal](https://www.paypal.com/).

2\. Navigate to the following:

Settings &gt; Account Settings &gt; Website payments under Products and Services &gt; Click the Updatelink under API Access.

![](/assets/images/paypal-payment/095cfb683a1428bfef075b6e92b34337.png)

 3. Under Custom checkout experience section, click Manage API credentials link under NVP/SOAP API integration (Classic) option:

![](/assets/images/paypal-payment/a6fa30a8396ebd6d912ca5869cff70da.png)

If you haven’t set it up before, you will be asked the following:

![](/assets/images/paypal-payment/6dc78bb81b0b583e56f46cc3f7e6bc36.png)

 Choose Request API signature and click the Agree and Submit button.

On the next page, copy the API Username, Password, and Signature generated. Click the Done button if you’re done.

![](/assets/images/paypal-payment/ffac48ed5cc2d426470b3730f38acea1.png)

You will have to remove existing credentials if you want to generate a new one. We, however, do not recommend removing this if you have existing integrations that use the credentials.

We highly recommend that you keep your API credentials safe for future reference.