# AWS-Risk-Labs
## Pipeline Controls Introduction

To complete this lab you will need to download three files.
- basic-sg-3-cfn.json
This is the CloudFormation script that will build our code pipeline.
- codepipe-single-sg.zip  
This file contains the CloudFormation scripts that will represent the change we are testing. It is a simple security group - A security group acts as a virtual firewall for your instance to control inbound and outbound traffic, and in this lab we are going to make sure it not open to the world before we allow it into production.  
- codepipeline-lambda.zip  
This file contains the code the code pipeline will run to execute the test against our change.
