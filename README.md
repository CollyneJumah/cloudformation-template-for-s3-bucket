## This is a cloudformation template to create an S3 bucket
- Using AWS CLI to create a stack:
`aws cloudformation create-stack --stack-name [STACKNAME] --template-body file://[TEMPLATE NAME.yaml]`

## Enable S3 versioning 
By modifying your stack and updating the existing stack
To update the stack:
`aws cloudformation update-stack --stack-name [STACKNAME] --template-body file://[TEMPLATE].yaml`

