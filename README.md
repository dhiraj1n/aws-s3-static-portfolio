# aws-s3-static-portfolio
Personal portfolio website hosted using Amazon S3 static website hosting.
# AWS Static Website Hosting Using Amazon S3

## Project Overview
This project demonstrates how to deploy a personal portfolio website using Amazon S3 Static Website Hosting.

The website is hosted on AWS without requiring an EC2 instance or managing a web server.

## Technologies Used
- Amazon Web Services (AWS)
- Amazon S3
- HTML5
- CSS3
- S3 Bucket Policy

## AWS Architecture

User Browser → Amazon S3 Website Endpoint → Website Files (HTML, CSS)

## Project Features
- Personal portfolio homepage
- About Me section
- Technical Skills section
- Projects section
- Contact section
- Custom CSS styling
- Custom error page

## AWS Implementation Steps
1. Created an Amazon S3 general-purpose bucket.
2. Enabled static website hosting.
3. Configured `index.html` as the index document.
4. Created HTML and CSS website files.
5. Uploaded website files to the S3 bucket.
6. Configured bucket-level public access settings.
7. Created a bucket policy granting public `s3:GetObject` permission.
8. Tested the website using the S3 website endpoint.

## Project Structure
```text
aws-s3-static-portfolio/
├── index.html
├── style.css
├── error.html
└── README.md
```

## Live Website
Paste your actual S3 website endpoint here.

## AWS Region
Asia Pacific (Mumbai) - ap-south-1

## Learning Outcomes
- Understanding Amazon S3 buckets and objects.
- Learning static website hosting.
- Understanding AWS bucket policies.
- Learning public read permissions.
- Deploying a website on cloud infrastructure.

## Future Improvements
- Configure Amazon CloudFront.
- Enable HTTPS using CloudFront.
- Connect a custom domain.
- Improve responsive website design.

## Author
Dhiraj Anjarlekar

Computer Engineering Student | Aspiring Cloud Engineer
