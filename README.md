# Security-hub-to-slack
Terraform Module to setup Security Hub to slack nofitication chennel

> Note: Required Terraform version >= 0.12 and also you can provide the AWS access details or it will using the default configuration.

It will create a `IAM role`, a CloudWatch `Log groups`, a EventBridge Rules for `SecurityHub`
and also a lambda function which will send the notification to the Slack chennel using the webhook URL.

