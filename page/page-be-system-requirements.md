<h4>1. Server Requirements</h4>
<ul style="text-align: justify;">
<li>Apache, Nginx, or another compatible web server.</li>
<li>PHP &gt;= 7.3 &gt;&gt; Higher</li>
<li>MySQL Database server 5.7.8.x</li>
<li>BCMath PHP Extension</li>
<li>Ctype PHP Extension</li>
<li>Fileinfo PHP extension</li>
<li>JSON PHP Extension</li>
<li>Mbstring PHP Extension</li>
<li>OpenSSL PHP Extension</li>
<li>PDO PHP Extension</li>
<li>Tokenizer PHP Extension</li>
<li>XML PHP Extension</li>
<li>Module Re_write server</li>
<li>PHP_CURL Module Enable&nbsp;</li>
</ul>
<p><strong>Minimum server</strong> space and RAM or processor, or resources are required on the hosting plan:&nbsp;<em><strong>&nbsp;RAM 2G, 1 CPU, 10GB Disk</strong></em></p>
<p><img src="" alt="" width="591" height="726" /></p>
<h4>2. PHP Configuration&nbsp;</h4>
<p>Open your php configuration file php.ini and change the following settings.</p>
<p><em><strong>memory_limit = 64M </strong></em></p>
<p><em><strong>max_execution_time = 3000</strong></em></p>
<p>If you are using Cpanel, you can follow this article to change your PHP memory limit settings <a href="https://chemicloud.com/kb/article/how-to-increase-the-php-memory-limit-in-cpanel/">https://chemicloud.com/kb/article/how-to-increase-the-php-memory-limit-in-cpanel/</a></p>
<p><strong>NOTE</strong></p>
<ul>
<li>
<p class="first">If you use Apache as your web server:</p>
<ul>
<li>
<p class="first"><strong>mod_rewrite</strong> should be enabled (for SEO to work);</p>
</li>
<li>
<p class="first"><strong>mod_headers</strong> should be enabled;</p>
</li>
<li>
<p class="first"><strong>mod_ssl</strong> should be enabled (for SSL to work);</p>
</li>
<li>
<p class="first"><strong>mod_security</strong> should be disabled; if you don&rsquo;t want to disable it fully, configure it to work with CS-Cart as described in <a class="reference download internal" href="/admin/module/knowleagebase/_downloads/mod_security.txt" download=""><code class="xref download docutils literal"><span class="pre">this</span> <span class="pre">file</span></code></a>;</p>
</li>
<li>
<p class="first">the <strong>.htaccess</strong> file should allow the following directives:</p>
<table class="colwidths-given table" border="0"><colgroup> <col width="20%" /> <col width="20%" /> <col width="20%" /> <col width="20%" /> <col width="20%" /> </colgroup>
<tbody valign="top">
<tr class="row-odd">
<td><code class="docutils literal"><span class="pre">DirectoryIndex</span></code></td>
<td><code class="docutils literal"><span class="pre">Deny</span></code></td>
<td><code class="docutils literal"><span class="pre">Allow</span></code></td>
<td><code class="docutils literal"><span class="pre">Options</span></code></td>
<td><code class="docutils literal"><span class="pre">Order</span></code></td>
</tr>
<tr class="row-even">
<td><code class="docutils literal"><span class="pre">AddHandler</span></code></td>
<td><code class="docutils literal"><span class="pre">RewriteEngine</span></code></td>
<td><code class="docutils literal"><span class="pre">RewriteBase</span></code></td>
<td><code class="docutils literal"><span class="pre">RewriteCond</span></code></td>
<td><code class="docutils literal"><span class="pre">RewriteRule</span></code></td>
</tr>
</tbody>
</table>
</li>
</ul>
</li>
</ul>
<p><strong>GD</strong> is included in PHP, however, PHP should be compiled with the <code class="docutils literal"><span class="pre">--with-gd</span></code> flag. The official PHP documentation has <a class="reference external" href="http://php.net/manual/en/image.installation.php">detailed installation instructions for GD</a>. Please make sure your GD configuration includes the <strong>FreeType</strong> font library.</p>
<blockquote style="background-color: #fcf8f2; border-left-color: #f0ad4e;">
<p>On this project, we're using the latest Laravel version (currently 8.x). Please go to Laravel documentation page for more information.</p>
<p>It&rsquo;s based on Laravel framework, the root folder for it is /public. You shouldn&rsquo;t install it on a sub-folder, use sub-domain is better than sub-folder. (we won&rsquo;t support to install our product on sub-folder) .</p>
</blockquote>