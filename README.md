# Terraform serverless API demo
> A simple serverless API with API Gateway, Lambda, DynamoDB, deployed with Terraform

## What it does

This Terraform example deploys an API Gateway invoking a Lambda function saving a form submission request into DynamoDB.

Look out for other Git branches for Proxy examples, IP whitelisting, IAM authentication, CORS support, caching and throttling, logging, monitoring and alerts

## Deployment

Update `terraform.tfvars` with appropriate AWS CLI profile and stack name values.
```sh
terraform init

terraform apply
```