##Simple website on S3 bucket with SSL cert

####Building parts:
1. AWS S3
2. AWS Cloudfront
3. AWS Route53
4. AWS CLoudformation

####Cloudformation variables:
BucketName - The DNS name of bucket
SSLcert - The Amazon Resource Name (ARN) of an AWS Certificate Manager (ACM) certificate
HostedDNSName - The DNS name of an existing Amazon Route 53 hosted zone

####How to
1. Apply s3-static-website.yaml for the domain
2. Upload your index.html to the S3 bucket 
