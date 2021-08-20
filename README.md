# My Experience, Feedback, And Tips for the AWS Developer Associate Exam

I passed the AWS Certified Developer Associate test on my first try a few weeks ago. My second attempt at the trial was having previously obtained AWS Developer Associate certification around four years ago. Since then, the test has undoubtedly altered. In the past, you could easily pass the test using knowledge from the [AWS Certified Solutions Architect Associate] and a few extra facts about Amazon DynamoDB. The latest exam is unquestionably more developer-focused, with questions evaluating your grasp of Developer Tools, development best practices, and code examples.

[//]: # (Any comments)
[AWS Certified Solutions Architect Associate]: <https://www.netcomlearning.com/certification/aws-certified-solutions-architect-associate/599/?advid=1356>

I still don't think you need a solid background in development to pass this exam. Indeed, my experience is in Enterprise Solutions Architecture rather than programming. You will need to comprehend some basic code examples, such as JSON code, configuration files, and IAM policy documents, although these are pretty simple. This is a credential that anybody, regardless of background, may obtain with the proper training.

In this post, I'll go through the test blueprint, provide some input from my exam experience, and offer some advice on effectively preparing for this exam. Of course, all exam takers must sign a non-disclosure agreement (NDA) that precludes me from discussing exam subject specifics.  

### General Information About the Exam:

•	AWS Certified Developer Associate is an abbreviation for Amazon Web Services Certified Developer Associate 

•	The length of the questionnaire is 65 questions.

•	Duration: 130 minutes

•	Passing grade: 720 points out of a possible 1000 points.

•	On the test, there are two sorts of questions:

•	Multiple-choice: There is one correct answer and three wrong answers (distractors)

•	Multiple response: Has two or more accurate replies from a set of five or more possibilities. (I only saw four of them out of 65 questions.)

•	Exam Guide for the [AWS Certified Developer Associate]

[//]: # (Any comments)
[AWS Certified Developer Associate]: <https://www.netcomlearning.com/certification/aws-certified-developer-associate/602/?advid=1356>

## What should I study?

Here is a list of services and some crucial subjects I believe you should learn before taking the exam. There is a strong emphasis on serverless application development, so make sure you are well-versed in the first five services listed below.
Listed in ascending order of significance (the first five services made up over 50 percent of my exam)

### AWS LAMBDA (10–15 % OF THE EXAM)

Types of invocation

•	Using event source mappings and notifications

•	X-Ray concurrency and throttling, as well as Amazon SQS DLLs

•	Aliases and variants

•	The use of blue and green deployment

•	VPC connection packaging and deployment (with Internet/NAT GW)

•	ELB target Lambda

•	Dependencies

### DYNAMODB AMAZON (10 percent OF THE EXAM)

•	Query vs. Scans (and the APIs, parameters you can use)

•	Secondary indices at the local and global levels

•	Calculating RCUs (Read Capacity Units) and WCUs (Write Capacity Units) (WC)

•	Best techniques for performance and optimization

•	Case studies (for example, session state, key/value data storage, and scalability)

•	Streams in DynamoDB

•	Use with Lambda and API Gateway in a serverless app.

•	Use cases for DynamoDB Accelerator (DAX)

### AMAZON API GATEWAY (8%–10% OF THE EXAM)

•	Authorizers for Lambda, IAM, and Cognito

•	Cache invalidation

•	Types of integration: proxy vs. bespoke / AWS vs. HTTP Caching

•	importing and exporting Swagger standards for OpenAPI

•	Variables at each stage

•	Metrics of performance

### AWS COGNITO (7%–8% OF THE EXAM)

•	Identity pools vs. User pools

•	An identity that has not been authenticated

•	AWS Cognito Sync with Cognito Web Identity Federation Using MFA

### AMAZON S3 (7%–8% OF THE EXAM)

•	Encryption – needs to unmake sure you understand S3 encryption well before taking the exam!

•	Versioning Data Copying Data Lifecycle Rules S3 Transfer Acceleration

### IDENTITY AND ACCESS MANAGEMENT (IAM) ON AMAZON IAM POLICIES AND ROLES

•	Access to multiple accounts

•	API calls for multi-factor authentication (MFA)

•	IAM Roles in EC2 (instance profiles)

•	Roles vs. access keys

•	Federation of IAM Best Practices

### ELASTIC CONTAINER SERVICE ON AMAZON (ECS)

•	Containers share storage space.

•	Single-docker environments vs. multi-docker environments

•	Using ECR to upload and download pictures

•	Methods of placement (e.g., spread, binpack, random etc.)

•	Mappings of ports

•	Task definitions must be defined.

•	Task Roles in IAM

### ELASTIC BEANSTALK ON AMAZON

•	Blue/green deployment policies

•	extensions and configuration files

•	Deployment updates

•	Worker tier vs. web tier

•	Deployment, packaging, and files, as well as code and commands, are all utilized.

•	Case studies

### CLOUD FORMATION ON AWS

•	Anatomy of a CloudFormation template (e.g., mappings, outputs, parameters, etc.)

•	AWS Serverless Application Model was utilized for packaging and deployment, including instructions (SAM)
