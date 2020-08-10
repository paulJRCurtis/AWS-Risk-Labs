# AWS-Risk-Labs
## Pipeline Controls Introduction

To complete this lab you will need to download three files.  

- basic-sg-3-cfn.json  
This is the CloudFormation script that will build our code pipeline.
- codepipe-single-sg.zip  
This file contains the CloudFormation scripts that will represent the change we are testing. It is a simple security group, and in this lab we are going to make sure it is not open to the world before we allow it into production.  

**Note the Security Group in the file includes ingress for Port 22 open to 0.0.0.0/0 - this is NOT a secure configuration**

This file is provided to show how such a configuration can be blocked using preventative controls.

- codepipeline-lambda.zip  
This file contains the source code for the Lambda functions the pipeline will run to execute the test against our change.

Special thanks to @adabalar1 for letting me reuse his code.
