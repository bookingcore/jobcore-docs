<p><span style="background-color: #f1f0f0;">1. How can remove "public" from url?</span></p>
<p><span style="background-color: #f1f0f0;">2. When people are clicking on my indexed pages through Google Search Engine It is taking the user to /public</span></p>
<p>We are using Laravel framework. As you know, its directory looks like this:</p>
<p><img src="/assets/images/c4145e1227ecd7f66f07371a9ea798a6.png" alt="" width="287" height="491" /></p>
<p>To open the homepage of my website (Route::get('/', 'HomeController@index');) I need to open /public folder of directory. In another word, to see the first page of my website here is the URL:</p>
<pre class="language-markup"><code>http://example.com/public
</code></pre>
<p>To resolve these issues, we did create a .htaccess file:</p>
<pre class="language-markup"><code>&lt;IfModule mod_rewrite.c&gt;
  RewriteEngine On
  RewriteRule ^(.*)$ public/$1 [L]
&lt;/IfModule&gt;</code></pre>
<p><em>But when people are clicking on my indexed pages through Google Search Engine It is taking the user to /public.&nbsp;</em></p>
<p>Follow Laravel framework Guideline, You have to change the root directory to the public folder to avoid security.&nbsp;In Cpanel, you can do it, but some hosting provider does not allow you to change for Primary domain. So, there are 3 solutions for you:</p>
<p>1. You need to contact your hosting provider to change the root directory of your primary domain to /public_html/pubic (now its /public_html)</p>
<p>2. You can change domain as add-on domain of your hosting package (because we can help you change for add-on domain easily)</p>
<p>3. You can move to another hosting provider that allows change root directory of the primary domain</p>
<p>&nbsp;</p>