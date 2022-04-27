# deploy-static-website-aws
The first project in Udacity DevOps Engineer patch, about hosting static
websites that only include HTML, CSS, and JavaScript files that require no
server-side processing. The whole project has two major intentions to implement. 
1. Hosting a static website on S3 
2. Accessing the cached website pages using CloudFront content delivery network (CDN) service.

PROJECT SPECIFICATION
https://review.udacity.com/#!/rubrics/2573/view

**Criteria 1**
The student has created a S3 bucket.

**Meet specification**
S3 bucket is visible in the AWS Management console. 
Screen shot in file s3buckets_details.pdf (staticwebproject1 - public)

**Criteria 2**
All website files should be added to the S3 bucket.

**Meet specification**
Screen shot in file s3bucket_objects.pdf shows all the website files uploaded
to the staticwebproject1 S3 bucket.

**Criteria 3**
The bucket configuration should be set up to support static website hosting

**Meet specification**
The S3 bucket is configured to support static website hosting. Details that
configuration is in the screen shot s3bucket_properties.pdf

**Criteria 4**
The permission access to the bucket should be configured.

**Meet specification**
The bucket should allow public access. The S3 bucket has an IAM bucket policy
that makes the bucket contents publicly accessible - screen shot
s3buckets_details.pdf

**Criteria 5**
The website should be distributed via Cloudfront.

**Meet specification**
CloudFront has been configured to retrieve and distribute website file. 
Screen shots: cloudfront_detail.pdf and cloudfront_main_page.pdf

**Criteria 6**
The website publicly accessible?
	
**Meet specification**
The website is accessible to anyone on the Internet via a web browser.

Origin domain:
staticwebproject1.s3-website.us-east-2.amazonaws.com

Distribution domain name:
https://d35mtpitgc30mb.cloudfront.net
