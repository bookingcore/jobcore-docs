<p><em>There&rsquo;s a certain amount of memory that the server will attribute to each site which it hosts. The default memory limit for Laravel is usually 32MB but processes such as importing the demo content and many other processes themes and plugins go through may require more memory. Increasing it will help you avoid some of the most common site errors.&nbsp;</em></p>
<h4><span class="wysiwyg-font-size-large">(Beginner) <em>Ask your&nbsp;hosting company</em> to increase the memory limit&nbsp;</span></h4>
<p>The easiest way is to reach out to your hosting company and ask them to increase the PHP memory allocated to your Laravel site to 256M.</p>
<p><em><strong>Recommended PHP configuration:</strong></em></p>
<ul>
<li>max_execution_time: 3000</li>
<li>memory_limit: 512M</li>
<li>post_max_size: 512M</li>
<li>upload_max_filesize: 512M</li>
</ul>