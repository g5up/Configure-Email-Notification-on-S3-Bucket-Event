<h1>Configure Email Notification on S3 Bucket Event!</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Company ABC is deploying a new web application that helps customers to upload files to S3 Bucket. As a part of the infrastructure, the Administrator needs to be notified via Email whenever an object is put into their S3 bucket. 





<h2>Languages and Utilities Used</h2>
- <b>Python</b> 

<h2>Environments Used </h2>
- <b>AWS</b> 

<h2>Program walk-through:</h2>

<p align="center">
Sign in to AWS Management Console
: <br/>
<img src="https://imgur.com/BmKYyNr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create an S3 Bucket.
: <br/>
<img src="https://imgur.com/8QXucbu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create an S3 Bucket.
: <br/>
<img src="https://imgur.com/H34C0IY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Navigate to the SNS service.
 <br/>
<img src="https://imgur.com/2zWfCYe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Create SNS topic.
 <br/>
<img src="https://imgur.com/34fMTFe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Click Create topic.
 <br/>
<img src="https://imgur.com/1lrVi0Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Click Subscription.
 <br/>
<img src="https://imgur.com/19Zs3pG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Create subscription.
 <br/>
<img src="https://imgur.com/fY74TC9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Navigate to Services > Lambda
 <br/>
<img src="https://imgur.com/5kKbXph.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Create Lambda function.
 <br/>
<img src="https://imgur.com/dsOEH8V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Create Lambda function: In the function code section, replace the default code with a Lambda function that sends a notification to the SNS topic.
 <br/>
<img src="https://imgur.com/bOGI4kg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Add trigger.
 <br/>
<img src="https://imgur.com/7FIRdcC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Add destination.
 <br/>
<img src="https://imgur.com/k8wPouw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Add destination.
 <br/>
<img src="https://imgur.com/k8wPouw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

 
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
