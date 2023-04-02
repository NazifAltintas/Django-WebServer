1. Create VPC and all components
    • Create VPC
    • Create Subnets
    • Create and attach an internet gateway
    • Create Route Tables
    • Create Endpoint
2 Create Security Groups (ALB ---> EC2 ---> RDS)
    • ALB Security Group
    • EC2 Security Groups
    • RDS Security Groups
    • NAT Instance Security Group
3. Create RDS
    • Create a subnet group for our custom VPC
    • Create Database
4. Create two 53 Buckets and set one of these as static website.
    • Failover Scenario
    • Web Site
5. Copy files downloaded or cloned from Techproeducation repo on Github
6. Prepair your Github repository
7. Prepare a userdata to be utilized in Launch Template
& Write RDS database endpoint and S3 Bucket name in settings file given by Developer and push your application into your own repo on Github
9. Create NAT Instance in Public Subnet
10. Create Launch Template and IAM role for it
11. Create certification for secure connection
12. Create ALB and Target Group
13. Create Autoscaling Group with Launch Template
14. Create Cloudfront in front of ALB
15. Create Route 53 with Failover settings
16. Create DynamoDB Table
17. Create Lambda function
18. Create S3 Event and set it as trigger for Lambda Function