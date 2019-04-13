In this lab we are going to prvision/deploy 3-tier architecture(Highly available and scalable) complete infrastructre On AWS in one go using CloudFormation template.

##multi-tier Infrastructure on AWS
It includes provisioning of below listed AWS resources:
VPC
Subnet
Security Group
EC2 Instance in two diff Availability Zone
ELB
Auto scaling grop
Network ACL
Internet Gateway
Route Table
Below diagram shows only 2-tier architecture, however JSON Template contains 3-tier architecture code. 
![iam](https://github.com/afaqueahmad/AWS_CloudFormation/blob/master/multi-tier.png)


Reference:
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html

## What is AWS CloudFormation?

AWS CloudFormation is a service that helps you model and set up your Amazon Web Services resources so that you can spend less time managing those resources and more time focusing on your applications that run in AWS. You create a template that describes all the AWS resources that you want (like Amazon EC2 instances or Amazon RDS DB instances), and AWS CloudFormation takes care of provisioning and configuring those resources for you. You don't need to individually create and configure AWS resources and figure out what's dependent on what; AWS CloudFormation handles all of that.


An easy way to create & manage a collection of aws resources.
Infrastructure as a code.
Allows orderly and predictable provisioning and updating of resources.
Allows you to version control your aws infrastructure.
Deploy and update the stacks using console, command line or API.
Best thing is you only pay the resources you create.



