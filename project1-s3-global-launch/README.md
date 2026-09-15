# AWS Static Portfolio Website

## Project Overview

This project is a personal portfolio website created as part of the DecodeLabs Cloud Computing Industrial Training – Project 1.

The objective of this project is to host a static HTML/CSS portfolio website on Amazon Web Services (AWS) using Amazon Simple Storage Service (Amazon S3).

The website demonstrates how a static website can be deployed to the cloud without provisioning or managing a traditional web server.

## Project Objective

The main objectives of this project are:

- Create a static portfolio website using HTML and CSS.
- Create an Amazon S3 bucket for website hosting.
- Upload the website files to the S3 bucket.
- Enable static website hosting.
- Configure appropriate public access permissions.
- Make the website accessible through a public URL.

## Technologies Used

- HTML5
- CSS3
- Amazon S3
- AWS Management Console
- Visual Studio Code

## Project Structure

```text
AWS-Portfolio/
│
├── index.html
├── style.css
└── README.md
```

### Files Description

**index.html**  
Contains the main structure and content of the portfolio website.

**style.css**  
Contains the styling and responsive design of the website.

**README.md**  
Contains information about the project, technologies, deployment process, and usage.

## Portfolio Sections

The website contains the following sections:

- Home
- About Me
- Education
- Technical Skills
- Projects
- Certifications & Learning
- Contact

## AWS Deployment

The website is deployed using Amazon S3 static website hosting.

### Deployment Steps

1. Create an S3 bucket in the AWS Management Console.
2. Upload `index.html` and `style.css` to the bucket.
3. Enable static website hosting.
4. Configure `index.html` as the index document.
5. Configure the required permissions for public website access.
6. Open the S3 website endpoint to test the deployed portfolio.

Amazon S3 static website hosting requires an index document, and the filename must exactly match the uploaded HTML file. In this project, the index document is `index.html`.

## Website URL

After deployment, the public S3 website endpoint will be added here:

**Live Website:**  
`YOUR-S3-WEBSITE-URL`

## Learning Outcomes

Through this project, I learned:

- Basics of Amazon S3.
- How to create and manage an S3 bucket.
- How to upload objects to Amazon S3.
- How static website hosting works.
- How to configure an index document.
- How cloud storage can be used to host static websites.
- Basics of AWS permissions and public access.
- How to deploy a website to the cloud.

## Future Enhancements

The project can be enhanced in the future by:

- Adding a custom domain.
- Adding HTTPS using Amazon CloudFront.
- Using Amazon CloudFront as a CDN.
- Adding JavaScript functionality.
- Improving the portfolio design.
- Adding more cloud projects and certifications.

## Author

**Cloud Computing Student**

B.Sc. Cloud Computing  
New Arts, Commerce and Science College, Ahilyanagar  
Maharashtra, India

## References

- AWS Amazon S3 Documentation
- DecodeLabs Cloud Computing Industrial Training – Project 1