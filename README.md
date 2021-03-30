# SQS ans SNS using Lambda in terraform

Clone this repo -
```
git clone https://github.com/AdityaPrakash2811/terraform-sqs-sns
```

Run the following commands -
```
terraform init
terraform plan
terraform apply
``` 

The tasks that have been done in this repo are -
- Configure the AWS Provider
- Create SNS topic
- Create SQS queue
- Create a DLQ for failed actions
- Crete SNS subscription
- Create SQS queue policy
- Creat Lambda function with required rules and policies.