# s3-static-website-hosting
# Static Website Hosting on Amazon S3

## Project Overview

This project demonstrates how to host a static website using Amazon Simple Storage Service (Amazon S3). The website was created with HTML and deployed to an S3 bucket configured for static website hosting.

## Objectives

- Create and configure an Amazon S3 bucket.
- Enable static website hosting.
- Upload an HTML website file.
- Configure a bucket policy for public read access.
- Test the website endpoint and troubleshoot deployment errors.

## AWS Services and Tools

- Amazon S3
- AWS Management Console
- HTML

## Implementation Steps

1. Created an S3 general-purpose bucket in the Europe (Stockholm) region.
2. Enabled static website hosting and configured `index.html` as the index document.
3. Created a simple HTML portfolio page.
4. Uploaded `index.html` to the bucket.
5. Configured bucket permissions and a bucket policy granting public read access to objects.
6. Tested the website endpoint and corrected an incorrectly configured index document name.

## Key Learnings

- How object storage and S3 buckets work.
- How to configure static website hosting.
- How bucket policies control access to objects.
- How to troubleshoot a `404 NoSuchKey` error.
- Why public access and HTTPS considerations matter when deploying websites.

## Security Considerations

This demonstration uses public read access. Only files intended for public viewing should be stored in the bucket. For production deployments, consider a private S3 bucket behind Amazon CloudFront, with HTTPS enabled.

## Future Improvements

- Add CSS and JavaScript files.
- Create a custom domain.
- Configure HTTPS through CloudFront.
- Automate deployment using a CI/CD pipeline.
