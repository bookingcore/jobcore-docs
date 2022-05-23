<p><strong>1. Enable HTTPs in .env file</strong></p>
<p>It is generally a good idea to encrypt traffic to your website. Do this by using HTTPS for your website. There are many benefits to moving to HTTPS. It also gives visitors to your site a feeling of security and trust.</p>
<p>Open your<strong>&nbsp;.env file</strong>&nbsp;then add the code:&nbsp;<code>APP_HTTPS=true</code>&nbsp;to enable HTTPS&nbsp;</p>
<p>&nbsp;</p>
<p><img src="/assets/images/911360f74b0866e4114c1f9dd64b77f6.png" alt="" width="817" height="387" /></p>
<p>&nbsp;</p>
<p><strong>2. Enable auto redirect to HTTPS in .htaccess file</strong></p>
<pre class="language-markup"><code>AddHandler application/x-httpd-php80 php

&lt;IfModule mod_rewrite.c&gt;
  RewriteEngine On
  RewriteRule ^(.*)$ public/$1 [L]
&lt;/IfModule&gt;

RewriteEngine On
RewriteCond %{HTTP_HOST} yourdomain\.com [NC]
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://yourdomain.com/$1[R,L]
</code></pre>
<p>&nbsp;</p>
<p><strong>3. Force HTTPS Redirection for your domains</strong></p>
<p>&nbsp;</p>
<p>If you are using hosting and Cpanel, you can Force HTTPS Redirection for your domains. Check this article:&nbsp;<a href="/admin/module/knowleagebase/edit/%20https:/blog.cpanel.com/force-https-redirection/#:~:text=In%20the%20Domains%20interface%20in,HTTPS)%20with%20a%20toggle%20switch"> https://blog.cpanel.com/force-https-redirection/#:~:text=In%20the%20Domains%20interface%20in,HTTPS)%20with%20a%20toggle%20switch</a></p>