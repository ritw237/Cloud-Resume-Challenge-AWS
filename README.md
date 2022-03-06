
# Cloud-Resume-Challenge-AWS-by-Ritwik-Srivastava

As I have trained for AWS CCP and giving the AWS CLF-C01 (Certified Cloud Practitioner) exam soon, I wanted to build a project using the AWS services I learned. And what better than the reputed Cloud Resume Challenge created by Forrest Brazeal.

Visit https://cloudresumechallenge.dev/docs/the-challenge/aws/ for more information on this challenge.

### Step 1 (Resume must have CCP cert)
Fingers crossed, I would have certainly passed the exam by the time you, the reader, is reading this repo.

### Step 2,3,7 ( written in HTML, CSS and JavaScript)

I made my portfolio website an year ago using some HTML, CSS and JavaScript and deployed it on vercel. It's a very simple website.
I have to add the visitor counter as said in Step 7
Visit https://ritwik.vercel.app

### Step 4 (deploy it using S3)
Need to remove it from vercel and then deploy it using Amazon S3. Or keep the same website and do the other steps

### Step 5 (using HTTPS)
Vercel already provides HTTPS but will use Amazon Cloudfront for this

### Step 6 (DNS)
will use Route53 if necessary

### Step 7 (JavaScript Visitor Counter)
I don't know how would this be added from the client's end, as I think it needs to be added on the server side (not confirmed)

### Step 8 (Database)
Will use DynamoDB for the visitor counter to retrieve and update the count from the database

### Step 9 (API)
API which will communicate with the web app and the Database

### Step 10 (Lambda Function)
I would finally get to use the famous AWS Lambda Function, will use boto3 library for AWS in python

### Step 11 (Tests)
Never done this before. Will write some tests for the python code

### Step 12 (Infrastructure as Code)
I will use AWS Serverless Application Model (SAM) template and deploy the DynamoDB table, the API gateweay and the lambda function, using the AWS SAM CLI.

### Step 13 (Source Control)
The challenge says to seperate the frontend and the backend code in separate repos. This is already done to an extent (still have to figure out adding the visitor counter)

### Step 14 (CI/CD backend)
Will set up Github Actions for the python code and tests

### Step 15 (CI/CD frontend)
Set up Github Actions for the website code, so the S3 bucket automatically gets updated

### Step 16 (Blog Post)
Finally, when all the above tasks are done, I will write a short blog post without all the code to finish the challenge and share my learnings.

