# An-intro-to-Amazon-SNS
lets talk a bit about Amazon SNS



# Amazon SNS - Simple Notification Service
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/uw7q7dbd1o672f6phtkx.png)

Amazon SNS is a fully managed Serverless solution from AWS. A message publishing and processing service. As it’s a serverless solution, with automatic scaling. Also allows fanout to millions of consumers. SNS topics can be an event topic and consumers can subscribe to that topic.
It is recommended to use a standard topic (High Throughput) . For Security enable Encryption , SNS support in-transit encryption by default but enabling SSE helps to encrypt the topic at-rest
Enable Redrive Policy to send undeliverable messages to a dead-letter queue(resiliency).
Features

Watch a 10 min intro from [aws.training](https://www.aws.training/Details/Video?id=15881 )
#Table of Contents
- [Anazon SNS - Simple Notification Service](#anazon-sns---simple-notification-service)
  - [Features](#features)
  - [Hands On Lab Links](#hands-on-lab-links)

## Features
- SNS support notification up to 12,500,000 per topic and 100,000 topics.
- Subscribers can be HTTP(S), SMS, SNS Mobile Push, Email/Email-JSON, SQS, Lambda functions.
- Pub / Sub Messaging
- SNS can create public topics
- SNS Supports Message archiving and analytics
- SNS is serverless –Do not have to worry about scaling out
- Message security Server-side encryption protects the contents of messages that are stored in Amazon SNS topics, using encryption keys provided by AWS KMS
- Redrive policy (dead-letter queue) - optional, can Send undeliverable messages to a dead-letter queue.

## Hands On Lab Links 
|🔗 Links            | What you learn                                                               |
| ----------------- | ------------------------------------------------------------------ |
| [A Cloud Guru](https://acloudguru.com/hands-on-labs/creating-and-subscribing-to-aws-sns-topics )| Create an SNS Topic,Create a Lambda Function , Send Your SNS Topic to Multiple Endpoints|
| [whizlabs.com]( https://play.whizlabs.com/site/task_details?task_id=32&quest_id=37 ) |Creating and Subscribing to SNS Topics, Adding SNS event for S3 bucket |
| [AWS Workshop](https://awsworkshop.io/tags/sns/) | Debug serverless applications with Lumigo , Applied Observability for Modern Applications with Epsagon |
|[CloudAcademy](https://cloudacademy.com/) | Amazon SNS Image Resizing Challenge|


###Read this blog in

|🔗 Links            |
| ----------------- |
|[ictpro.co.nz](https://ictpro.co.nz/2021/09/26/an-intro-to-amazon-simple-notification-service-sns/)|
|[dev.to](https://dev.to/aws-builders/amazon-simple-notification-service-sns-4gf7)|
