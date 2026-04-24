# Pulumi

**Different ways to create infrastrcuture in cloud** 

- via UI console of that respective cloud (AWS Console , GCP console , Azure console UI)
- via CLI (AWS CLI , gcloud CLI , azure cli (az))
- via python boto3 (via Cloud api's )
- via IAC (Cloud lockin - AWS Cloudformation)
- Terraform 
- Pulumi (Infrastructure via any programming language) 


**Introduction** 

- Pulumi is opensource 
- Supports 6 programming languages (Go , Java , Nodejs (TS,JS) , Python , C# , YAML)

Terraform drawbacks are 
- Its is licensed to closed source now so most companies are migrating to alternative opensource IAC tools 
- State management is difficult need to maintain state file and remote backend 
- HCL is a template language which doesnt support looping and conditionals like programming languages 


**Getting started** 

- Create an account in app.pulumi.com

`https://app.pulumi.com/signin?reason=401` 

- Install pulumi cli 

`https://app.pulumi.com/signin?reason=401` 

for connecting to AWS account we need to set up AWS credentials in our local machine and for that we can use AWS CLI and run the command `aws configure` and provide the access key and secret key of our AWS account. 

https://www.pulumi.com/docs/iac/get-started/aws/

terraform plan = pulumi preview

terraform apply = pulumi up 

terraform workspaces = pulumi stack 


in stack if you dev it means for development environment and prod for production environment and staging for staging environment and so on. same like teerraform workspaces.

terraform modules = pulumi components 

State management in pulumi is dont via app.pulumi.com and it is free to use for up to 5 users and 5 stacks.

terraform destroy = pulumi down 

