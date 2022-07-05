

# Cloud-Resume-Challenge [AWS]

## Hi, I'm Ritwik! 👋


As I have trained for AWS CCP and giving the AWS CLF-C01 (Certified Cloud Practitioner) exam soon, I wanted to build a project using the AWS services I learned.
(Edit:- I now have trained for AWS Solutions Architect Associate and will sit for the AWS SAA C02.)

And what better than the reputed Cloud Resume Challenge created by Forrest Brazeal, it's free and is designed for the newcomers in Cloud so they can use the AWS services in a hands-on project.

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
Vercel already provides HTTPS but will use Amazon CloudFront for this

### Step 6 (DNS)
will use Route53 if necessary

### Step 7 (JavaScript Visitor Counter)
I don't know how would this be added from the client's end, as I think it needs to be added on the server side (not confirmed)

### Step 8 (Database)
Will use DynamoDB for retrieving and updating the visitor counter

### Step 9 (API)
API which will communicate with the web app and the Database (AWS API Gateway will come into play here)

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


## Tech Stack

**Client:** HTML, CSS, JavaScript

**Server:** Python, boto3, AWS SAM, DynamoDB, AWS API Gateway, Github Actions, Amazon S3, Amazon CloudFront, Amazon Route 53
## Resources for research

 - [Tests for Lambda Functions](https://towardsdatascience.com/how-i-write-meaningful-tests-for-aws-lambda-functions-f009f0a9c587)
 - [Front-end with IaC](https://learn.hashicorp.com/tutorials/terraform/cloudflare-static-website?in=onboarding/tfcb-week-4)
 - [JavaScript Counter]()
 - [AWS SAM specification resources and properties](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/sam-specification-resources-and-properties.html)


## Feedback

If you have any feedback, please reach out to me on ritwik.srv237@gmail.com




