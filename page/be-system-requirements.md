# 1. Server Requirements

- Apache, Nginx, or another compatible web server.
- PHP &gt;= 8.0.2 &gt;&gt; Higher
- MySQL Database server 5.7.8.x
- BCMath PHP Extension
- Ctype PHP Extension
- Fileinfo PHP extension
- JSON PHP Extension
- Mbstring PHP Extension
- OpenSSL PHP Extension
- PDO PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension
- Module Re\_write server
- PHP\_CURL Module Enable
 
**Minimum server** space and RAM or processor, or resources are required on the hosting plan:  ***RAM 2G, 1 CPU, 10GB Disk***

![](/assets/images/be-system-requirements/28b27f968e9fc808d147a3b825cf8262.png)

#### 2. PHP Configuration 

Open your php configuration file php.ini and change the following settings.

***memory\_limit = 64M***

***max\_execution\_time = 3000***

If you are using Cpanel, you can follow this article to change your PHP memory limit settings <https://chemicloud.com/kb/article/how-to-increase-the-php-memory-limit-in-cpanel/>

**NOTE**

- If you use Apache as your web server:
    
    
    - **mod\_rewrite** should be enabled (for SEO to work);
    - **mod\_headers** should be enabled;
    - **mod\_ssl** should be enabled (for SSL to work);
    - **mod\_security** should be disabled; if you don’t want to disable it fully, configure it to work with CS-Cart as described in [`<span class="pre">this</span> <span class="pre">file</span>`](/admin/module/knowleagebase/_downloads/mod_security.txt);
    - the **.htaccess** file should allow the following directives:
        
                  `<span class="pre">DirectoryIndex</span>` `<span class="pre">Deny</span>` `<span class="pre">Allow</span>` `<span class="pre">Options</span>` `<span class="pre">Order</span>`   `<span class="pre">AddHandler</span>` `<span class="pre">RewriteEngine</span>` `<span class="pre">RewriteBase</span>` `<span class="pre">RewriteCond</span>` `<span class="pre">RewriteRule</span>`
 
**GD** is included in PHP, however, PHP should be compiled with the `<span class="pre">--with-gd</span>` flag. The official PHP documentation has [detailed installation instructions for GD](http://php.net/manual/en/image.installation.php). Please make sure your GD configuration includes the **FreeType** font library.

> On this project, we're using the latest Laravel version (currently 8.x). Please go to Laravel documentation page for more information.
> 
> It’s based on Laravel framework, the root folder for it is /public. You shouldn’t install it on a sub-folder, use sub-domain is better than sub-folder. (we won’t support to install our product on sub-folder) .

[Civi Elements](#block-jobcat)
==============================

###### Dashboard > Templates > Build Template

#### Job Categories

This is the way it shows on Home page, there are 2 styles for list Job category:

**Style 1:** The icon image is placed on the left side

![](/assets/images/elements/jobcatlist.png)

**Style 2:** The icon image is placed on the left side

![](/assets/images/elements/jobcatlist2.png)

**Style 3:** The icon image is centered above

![](/assets/images/elements/jobcatlist3.png)

To build this element, go to Template and find **Job Categories**, select style you need to use, input the **Title, sub-title, select the category you need to show in this section**

![](/assets/images/elements/jobcatbk.png)