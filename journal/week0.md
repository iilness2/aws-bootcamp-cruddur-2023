# Week 0 — Billing and Architecture

## Getting the AWS CLI Working

### Install AWS CLI
Signup to gitpod using github and start installing AWS CLI when Gitpod launches
![Install AWS CLI](assets/week0-install-aws-cli.png)

### Create a new User and Generate AWS Credentials

Created new user called Andre and created Access Key as well

![New IAM user](assets/week0-create-new-user-and-generate-aws-creds.png)

![Downloaded aws creds](assets/week0-aws-creds-download.png)

### Set Env Vars

![Set env vars](assets/week0-set-env-vars.png)

### Check that the AWS CLI is working and you are the expected user

Run this code in terminal and get the caller identity

```
aws sts get-caller-identity
```

![Caller identity](assets/week0-caller-identity.png)

### Enable Billing

![Enable billing](assets/week0-enable-billing.png)

### Creating a Billing Alarm

#### Create SNS Topic

1. Create SNS Topic and subscribe supply the TopicARN

![Create SNS Topic](assets/week0-create-sns-topic.png)

> Make sure topic is created through AWS console

![Create SNS Topic](assets/week0-topic-created.png)

2. Confirm the subscription from received email from AWS

![Received subscription confirmation mail](assets/week0-subscription-sns-confirmation-mail.jpeg)

![Confirmed subscription](assets/week0-subscription-confirmed.jpeg)

> Make sure topic's subcription is confirmed through AWS console

![Confirmed topic's subscription](assets/week0-topics-subscription-confirmed.png)

#### Create Alarm

![Create alarm](assets/week0-create-alarm.png)

> Make sure alarmed is created through AWS console and suddenly get email from it

![Check alarm is created](assets/week0-check-alarm-is-created.png)



### Create an AWS Budget

1. Get AWS Account ID and set it as env

![Set Account Id as env](assets/week0-set-account-id-as-env.png)

2. Update json files by copying example from budget.json & budget-notifications-with-subscribers.json

![Add budget json and its notification](assets/week0-add-budget-json-and-its-notification.png)

3. Create budget using cli command

![Budget is created](assets/week0-budget-is-created.png)

