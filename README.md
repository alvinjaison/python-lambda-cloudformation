# python-lambda-cloudformation
A cloudformation template for creating a python lambda with an IAM role

Create the cloudformation stack from AWS console or using aws-cli
   ```
   aws cloudformation create-stack --stack-name riFinder --template-body file://riFinderCFTemplate.yaml
   ```
   
   The cloudformation will create the following resources
   > An IAM role

   > A Python Lambda function for listing all reserved instances in the account
