# PROJECT ONE

## PROJECT TOPIC: Deploying Static Website on AWS

-------
**Name**: Nwachukwu Tochukwu Charles <br/>
**Email Address** : tochinwachukwu33@gmail.com

-------

### **PROJECT DELIVERABLES:**

STATIC S3 WEBSITE ENDPOINT: <http://travel-blog-site.s3-website.eu-west-3.amazonaws.com/> <br/>
CLOUDFRONT DISTRIBUTION ENDPOINT: <https://d3iigt7bowbu6p.cloudfront.net/>

-------

## **Steps taken in deploying a Static Website on s3**

1. I navigated to the s3 service in the AWS console.
2. I created an s3 bucket and named it s3 bucket
3. I set the bucket Visibility to public
4. The following access control policies were added to make sure that the contents of the bucket are visible to the public
5. CORS policies were configured on the bucket to ensure that resources from the bucjet can be viewed by the browser.
6. The files were unziped and uploaded to the bucket, making sure that the index.html is present in the root folder
7. I navigated to the properties settings and enabled static website hosting for the bucket
8. I created set index.html to be both the index page and the error page for the site.
9. The site can be accessed via this link: <http://travel-blog-site.s3-website.eu-west-3.amazonaws.com/>

## Steps taken in creating a CloudFront Distribution

1. The static endpoint of the website was copied.
2. CloudFront service was started and the website endpoint was placed as the origin of the distribution.
3. A redirect rule was placed that redirects all http traffic to https.
4. All other settings were left as default
5. The create distribution button was hit
6. The distribution endpoint: <https://d3iigt7bowbu6p.cloudfront.net/>

<br/>

## PROJECT SCREENSHOTS

1. The s3 bucket service is opened up
 ![The s3 bucket service is opened up](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/Screenshot+2022-08-05+080329.png)

2. Creating an s3 bucket:
![Creating an s3 bucket](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659727457649.png)

3. The s3 bucket is created
 ![The s3 bucket is created](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659727614235.png)

4. Bucket versioning is enabled
![Bucket versioning is enabled](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659727514021.png)

5. Allowing public access to the s3 bucket
 ![Allowing public access to the s3 bucket](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659727495833.png)

6. The access control configurations are modified in the permissions tab
 ![The access control configurations are modified in the permissions tab](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659727648789.png)

7. Bucket policies are set to allow public read access to all contents of the bucket (*)
 ![Bucket policies are set to allow public read access to all contents of the bucket (*)](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659728000659.png)

8. Website static files are uploaded to the s3 bucket
 ![Website static files are uploaded to the s3 bucket](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659728187007.png)

9. The static files are done uploading
 ![The static files are done uploading](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659729515148.png)

10. Static website hosting is enabled for the bucket
 ![Static website hosting is enabled for the bucket](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659729538213.png)

11. Static website hosting is turned on
 ![Static website hosting is turned on](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659729552198.png)

12. The index and error documents are specified for the website endpoint
 ![The index and error documents are specified for the website endpoint](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659729576982.png)

13. The Website endpoint is now available
 ![The Website endpoint is now available](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659729631385.png)

14. A CloudFront Distribution is created for the website endpoint
 ![A CloudFront Distribution is created for the website endpoint](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659729183182.png)

15. CloudFront is set to redirect all http reuests to https
 ![CloudFront is set to redirect all http reuests to https](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659732143839.png)

16. Once the distribution is created, it can be accessed via the https secure link
 ![Once the distribution is created, it can be accessed via the https secure link](https://travel-blog-site.s3.eu-west-3.amazonaws.com/screenshots/1659729467516.png)
