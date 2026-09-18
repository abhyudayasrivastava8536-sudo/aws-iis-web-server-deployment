# aws-iis-web-server-deployment
Deployment of an IIS web server on AWS EC2 using Windows Server, including security group configuration and public web access.

## Overview

This project was a hands-on cloud deployment exercise where I launched a
Windows Server EC2 instance on AWS and configured IIS to host a static website.

## Technologies Used

- AWS EC2
- Windows Server
- IIS
- AWS Security Groups

## What I Did

1. Created and launched an EC2 instance using Windows Server.
2. Connected to the instance using Remote Desktop.
3. Installed IIS Web Server.
4. Created and configured the website.
5. Configured the EC2 security group to allow the required traffic.
6. Tested the website using the public IP address of the EC2 instance.

## Architecture

User
   |
   v
Public Internet
   |
   v
AWS Security Group
   |
   v
EC2 - Windows Server
   |
   v
IIS Web Server
   |
   v
Static Website

## What I Learned

This project helped me understand how a cloud virtual machine is created
and accessed, how security groups control network access, and how a web
server can be deployed on a cloud instance.

I also learned that deployment is not only about starting a server.
Networking and security configuration are equally important for making
the application accessible.

## Screenshots

Screenshots of the EC2 instance, security group configuration, IIS
configuration and deployed website are included in the screenshots folder.
