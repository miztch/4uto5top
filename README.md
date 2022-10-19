# 4u70570p

You can pronounce "auto-stop"!

## What this Lambda function does
- stop all EC2 instances 
- stop all RDS instances
- terminate EC2 instances in all AutoScaling groups

This function is triggered by EventBridge Event, and affects to the resources in the region deployed.

## Provisioning

You can use [AWS SAM](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html) to provision this function.

```bash
sam build
sam deploy --guided
```
