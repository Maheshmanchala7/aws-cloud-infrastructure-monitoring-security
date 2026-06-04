# AWS Cloud Infrastructure Monitoring & Security

## Project Overview

This project demonstrates the implementation of monitoring, alerting, auditing and security services in AWS using EC2, RDS, CloudWatch, SNS, CloudTrail and S3.

The objective is to improve infrastructure visibility, monitoring and security through automated alerts and centralized logging.

## Architecture

EC2 Instance → CloudWatch → SNS Email Alerts

AWS Services → CloudTrail → Amazon S3 Log Storage

Amazon RDS → Managed Database Service

## Services Used

* Amazon EC2
* Amazon RDS
* Amazon CloudWatch
* Amazon SNS
* AWS CloudTrail
* Amazon S3

## Features

* Infrastructure Monitoring
* CPU Utilization Alerts
* Email Notifications
* Cloud Activity Auditing
* Centralized Log Storage
* AWS Security Monitoring

## Project Workflow

1. Created EC2 Instance
2. Configured Amazon RDS Database
3. Created SNS Topic and Email Subscription
4. Configured CloudWatch Alarm
5. Triggered Alarm and Verified Email Notification
6. Created CloudTrail
7. Stored Audit Logs in Amazon S3
8. Verified CloudTrail Log Generation

## Skills Demonstrated

AWS, EC2, RDS, CloudWatch, SNS, CloudTrail, S3, Monitoring, Logging, Auditing, Cloud Security, Linux

## Outcome

Successfully implemented a cloud monitoring and security solution capable of generating alerts, auditing AWS activities and storing logs centrally for operational visibility and security.
## Project Screenshots

### EC2 Instance
![EC2](screenshots/ec2-instance.png)

### RDS Database
![RDS](screenshots/rds-instance.png)

### SNS Topic
![SNS](screenshots/sns-topic.png)

### SNS Subscription
![SNS Subscription](screenshots/sns-subscription.png)

### CloudWatch Alarm
![CloudWatch](screenshots/cloudwatch-alarm.png)

### Alarm Email Notification
![Alarm Email](screenshots/alarm-email.png)

### CloudTrail Created
![CloudTrail](screenshots/cloudtrail-created.png)

### CloudTrail Logging
![CloudTrail Logging](screenshots/cloudtrail-logging.png)

### S3 Log Bucket
![S3 Bucket](screenshots/s3-log-bucket.png)
