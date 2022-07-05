Navigate to ***SYSTEM SETTINGS &gt; FILE SYSTEM SETTINGS &gt;*** select **AWS S3:**

![](/assets/images/aws-s3/139e15895b2ac668477bb55515c17935.png)

#### How to create AWS Access Key + Secret Access key?

1\. Login to <https://aws.amazon.com/>

![](/assets/images/aws-s3/8781c0761703f2005ad461db80f3295f.png)

2\. On the AWS Menu &gt; Services &gt; click Security identity &gt; IAM

![](/assets/images/aws-s3/636ed6980441c90e6ed570d7de3c37e0.png)

3\. On the **IAM Dashboard**, find **Users**

![](/assets/images/aws-s3/63a230bd023e82b0b6db772385ea7cc8.png)

**4. Press "Add new User"**

![](/assets/images/aws-s3/74fab11c50832b17c725aaffefd19cbd.png)

Input **User name** and select **AWS credential type: Access Key**

![](/assets/images/aws-s3/e5afae68ad6ab788c98bafff53493130.png)

**5. Add the user to a group,** we will select a Group with the **Attached policies: AmazonS3FullAcess**

![](/assets/images/aws-s3/b5f86c25270d5e97ea3fa49172c247f6.png)

**Press to Next Review**

**![](/assets/images/aws-s3/1875e80059b4d89b77cc4aed57f8499f.png)**

**All information is here, press "Create User" to complete creating a user**

![](/assets/images/aws-s3/5e469d61d348533327c2a3c624af83c6.png)

**Copy the Access key ID + Secret access key**

![](/assets/images/aws-s3/4cc891e44638903cf990defff9aa644b.png)