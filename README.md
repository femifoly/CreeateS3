# Creeate S3 Bucket

#### What is AWS S3?

Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. You can use Amazon S3 to store and retrieve any amount of data at any time, from anywhere.

#### How to create S3 bucket

* Login to AWS console
----
![](https://github.com/femifoly/CreeateS3/blob/main/S3/singin.png) 
----

* Type s3 in the search bar to pull up the service
----
![](https://github.com/femifoly/CreeateS3/blob/main/S3/s3search.png)
----

* Click create bucket
* Name your bucket with a globally unique name in a region
* Configure the ACL and public access

----
![](https://github.com/femifoly/CreeateS3/blob/main/S3/creates3.png)
----

* Click on create bucket
----

![](https://github.com/femifoly/CreeateS3/blob/main/S3/creates3last.png)
----

This will create our input S3 bucket in the chosen region (us-east-1) and we can repeat the same steps to create our output bucket in the same region.

----


#### How to upload objects into S3 bucket

* Click on the bucket you want to upload files into
----
![](https://github.com/femifoly/CreeateS3/blob/main/S3/upload1.png)
----
* Click on add files and select the files to be uploaded from your file explorer. You can upload multiple files without having to upload each file.
* The files can finally be uploaded into your S3 bucket by clicking upload at the botoom.
----
![](https://github.com/femifoly/CreeateS3/blob/main/S3/upload2.png)
----

These steps will upload the selected files into the S3 bucket and you will be able to view the file name, type and status of the uploads once succesful.

----
![](https://github.com/femifoly/CreeateS3/blob/main/S3/uploadlast.png)


# Create a Lambda Function

#### What is AWS Lambda?
AWS Lambda is a serverless compute service that runs your code in response to events and automatically manages the underlying compute resources for you.
Since we can run whisper using python language, it is easy for us to test and translate our Albanian audio by triggering Lambda functions to carry out these tasks.
Using AWS S3, lambda and whisper to do speech to text has many advantages. Itt's cost effective, scalable and eaasy to use.

#### Benefits of Lambda
* Serverless Architecture
* Code freely
* No VM needs to be created
* Pay-as-you-go
* Monitor Performance

#### How to install AWS Lambda

