# Deploying a Static Website Using AWS S3 and CloudFront (My Capstone Project)

Overview
This project outlines the deployment of a static website on AWS using:

- Amazon S3: Object Storage Solution
- Amazon CloudFront: Global Content Delivery Network (CDN)
- CloudFront Origin Access Control (OAC): Secure Bucket Access Mechanism

The website is hosted on S3 and distributed via CloudFront, ensuring low-latency access worldwide.

Architecture
User → CloudFront → S3 Bucket → Static Files

CloudFront handles:
- Global caching and distribution
- Secure access to S3 via HTTPS
- SSL/TLS encryption for secure data transfer

S3 stores:
- index.html
- styles.css
- script.js

Deployment Steps
1. Created and configured an S3 bucket for static website hosting
2. Uploaded website files to the S3 bucket
3. Implemented bucket policy for secure CloudFront access
4. Created and configured a CloudFront distribution
5. Set the default root object to index.html
6. Verified global accessibility via the CloudFront URL

Screenshot Images
1. S3 Website Endpoint ![images/deployment-screenshot.png](https://github.com/amgbaduba/My-Capstone-Project/blob/4e3111813c1762ae24f67b92018bfb5a088d5688/images/!.jpeg)
2. CloudFront Distribution ![images/cloudfont-screenshot.png](https://github.com/amgbaduba/My-Capstone-Project/blob/4e3111813c1762ae24f67b92018bfb5a088d5688/images/!!.png)
3. S3 Successful File Upload ![images/S3-flie-upload-screenshot.png](https://github.com/amgbaduba/My-Capstone-Project/blob/4e3111813c1762ae24f67b92018bfb5a088d5688/images/!!!.jpeg)

Technology Stack
- HTML5
- CSS3
- JavaScript (ES6+)
- Amazon S3
- Amazon CloudFront

Author
<p>AMGBADUBA EMMANUEL EBIKPOLADE

Cloud Engineering (AWS) Capstone Project @ (link unavailable)</p>
