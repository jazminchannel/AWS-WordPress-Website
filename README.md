# AWS-WordPress-Website
In this project, I created a Wordpress blog website in AWS using a AMI I created as a base image. I used packer and ansible to create a golden AMI. The users post are being stored in an Amazon Aurora database. I have also added a custom domain name through Route 53 and attached a SSL certificate for HTTPS via Certificate Manager.

## Application Breakdown

The application is broken down into the architecture below:

![wordpress](https://github.com/jazminchannel/images/blob/main/wordpressv2)
