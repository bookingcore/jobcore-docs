<p>To Enable Stripe payment on your site, please follow these steps below:</p>
<p>1. Go to Dashboard &gt; Settings &gt; Payment settings &gt; Stripe Checkout &gt; Enable Stripe Checkout V2</p>
<p>2. Input&nbsp;Secret Key +&nbsp;Publishable Key +&nbsp;Webhook Secret</p>
<p><em>Some optional options: Custom Name / Description / Logo </em></p>
<p><em>+ Sandbox Mode is for testing</em></p>
<p><img src="/assets/images/stripe-payment/dd316a24ad6ee30c46886831e837956f.png" alt="" width="831" height="745" /></p>
<h5>1. How to get Secret API key</h5>
<p>To obtain your Stripe Secret Key, follow these steps below:&nbsp;</p>
<p>1. You need to log in to your Stripe account.</p>
<p>2. In the dashboard view, navigate to the left side menu,&nbsp;</p>
<p>first click on &lsquo;Developers&rsquo; and select &lsquo;API keys&rsquo;. This will display a screen on the right-hand side.</p>
<p>3. Under &lsquo;Standard keys&rsquo;, you will see &lsquo;Secret key&rsquo; and a button named &lsquo;Reveal live key&rsquo;.</p>
<p>Click on the button and it will display the secret key.</p>
<p>Or read more here: <a href="https://stripe.com/docs/keys">https://stripe.com/docs/keys</a></p>
<p><img src="/assets/images/stripe-payment/887fcfb8345d825cda43b01886b11858.png" alt="" width="1280" height="382" /></p>
<h5>2. Steps to receive webhooks&nbsp;</h5>
<ol>
<li>Go to your Stripe log in &gt; Add a Webhook, input webhook link, ex: Webhook URL: <a href="http://dev.bookingcore.org/gateway/gateway_callback/stripe">http://linkURL.com/gateway/gateway_callback/stripe</a>&nbsp;</li>
<li>Then a secret key will be generated, Copy the Signing secret key and input it to Webhook secret key field in the Setting</li>
</ol>
<p><img src="/assets/images/stripe-payment/ce16c628f469a039a83086bbee85ea78.png" alt="" width="1130" height="824" /></p>