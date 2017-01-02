As of the writing of this (2017-01-01) accounts are free for 12 months, however you will need to enter payment information.

Note: The instructions a references to AWS tutorials below will show you how to host your application on a sub-subdomain of elasticbeanstalk.com, and update that application via .zip file uploads.

For instructions on how to host applications on vanity URLS, click here.
For instructions on how to setup FTP updates to AWS, click here.

##Personal Account Creation
Step 1 - Contact Information
Step 2 - Payment Information
Step 3 - Identity Verification by phone
	- enter a 4 digit code via phone that is displayed on the screen
Step 4 - Support Plan
	- choose from several options for the type of plan you want
	- I selected Basic for this tutorial
Step 5 - Confirmation
	- after hitting submit on the Support Plan selection page your account will be setup and the following screen will ask you a few questions to "Personalize Your AWS Experience"
	- Use Case: Website
	- Job Role: Developer / Engineer
	- Industry: Other
	- Organization: Self Employed
	- What are you using AWS for: Personal Use

##Launch a Web Application
AWS provides many tutorials for getting started. I chose to follow the launching a web application tutorial.

From the tutorial:
"This step-by-step guide will help you get a sample PHP application up and running with AWS Elastic Beanstalk (EB). EB supports other languages besides PHP, such as Java, .NET, Node.JS, Python, Ruby, Docker, and Go, but the focus of this tutorial will be on PHP (other languages will follow the same process). You will first configure your EB application, then setup your EB environment where your application will be launched into.""

Following this paragraph are instructions for downloading the sample PHP application and launching the AWS management console. The link to the management console opens in a new browser, but does not immediately take you to the previewed screen in the tutorial. Click on "Services" to be shown the "Elastic Beanstalk" option.

On step 3 of the tutorial you are asked to Configure your environment. Make sure to remember where you saved the sample .zip file.

The instructions for the AWS tutorial were a little outdated, but once you upload the .zip file and click next the Virtual Private Cloud will innitiate. This will take several minutes, but once you have a success message, navigate to Services > Eleastic Beanstalk, and the VPC should appear as a green box on your dashboard called "Sample-env".






