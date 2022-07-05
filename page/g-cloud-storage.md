Navigate to ***SYSTEM SETTINGS &gt; FILE SYSTEM SETTINGS &gt;*** select ***GOOGLE CLOUD STORAGE***:

![](/assets/images/g-cloud-storage/f3a5bdab4abe206d313754447a8718fe.png)

\* If your system does not host on Google Cloud, you need to upload your Service Account Key File to folder: */home/freshen.be-commerce.org/storage/app/gcs*, then copy the file name to the input above, Example: project-name-xxx-xxx.json  
\* If running in Google App Engine, the built-in service account associated with the application will be used.  
\* If running in Google Compute Engine, the built-in service account associated with the virtual machine instance will be used.

#### How to create a Google Cloud Service Account and download client json file

1\. The first thing you want to do is we want to go to [console.cloud.google.com](https://console.cloud.google.com/).

2\. And once you get to the homepage which is the dashboard you want to click on the navigation menu

3\. Then click on **IAM &amp; Admin**. From the menu items, I want to select **Service accounts**.

![](/assets/images/g-cloud-storage/01924900357cae7a72f19d88aa6b887e.png)

On the top, click on **create a service account**.

![](/assets/images/g-cloud-storage/6ef1f7fdd29cd83cd6cb9c5ec6fc18b6.png)

Here I want to **give our account a name**. For example, I can name my service account

freshen-gg-could-admin

to imply that this account has full access to everything. You can also add additional

information in the description field to give more detail on the purpose of the account,

then click on Create and continue.

![](/assets/images/g-cloud-storage/553fbbb6ce21f318a066ea4b2ffec2cf.png)

Now, we will select a role to assign to this account.

So different role has different permissions set to different cloud products. Since I'm the owner, I'm going to click on basic

And we're going to choose the **Storage Admin** and **Storage Admin** will give me full access to all the resources.

![](/assets/images/g-cloud-storage/732caeb406898025387ee386c73894c0.png)

Service account's privilege. You can type in the user's, email address or the group

You can leave 2 fields in this step blank

Then Done

![](/assets/images/g-cloud-storage/4087379c48c7b30ed350756a1076d2d6.png)

Notice in the under the key ID field, this account doesn't have a key id assigned. So need to create a new set of key ID.

to do that **under the actions column &gt; click on manage keys**.

![](/assets/images/g-cloud-storage/327922ea357f6e67aec40da1154ad3da.png)

Now click on **ADD key** and click **create new key for the key type** &gt; **Json** and click on **create**.

![](/assets/images/g-cloud-storage/923e11b789465991dbbc3d6878fdc12b.png)

The dialogue window's going to prompt you to **save** the client file. I'm going to save the file

![](/assets/images/g-cloud-storage/31fbef8eaac5a861f03f367bfe9d9d7c.png)