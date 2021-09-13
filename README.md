# README #
Based on https://cloudonaut.io" templates
## Description
- *wecari-alert.yaml*  - SNS Notification for AWS Infrastructure alerts
- *wecari-vpc.yaml* - VPC
- *wecari-vpc-nat.yaml* - NatGateway in VPC
- *wecari-vpc-nat-instance.yaml* - VPC: NAT Instance in an Auto Scaling Group
- *wecari-bastion.yaml* - Bastion Host (EC2 Instances in Auto Scaling Group)
- *wecari-alb.yaml* - Application Load Balance
- *wecari-ecs.yaml* - ECS Cluster of EC2 instances in an Auto Scaling Group
- *wecari-ecs-efs.yaml* - ECS Cluster of EC2 instances in an Auto Scaling Group With EFS for Code storage
- *wecari-ecs-service.yaml* - ECS Service Rolling Update Deployment
- *wecari-ecs-service-php.yaml* - ECS Service for Laravel with Rolling Update Deployment
- *wecari-ecs-deploy.yaml* -Continuous Delivery to ECS for Laravel Project using Rolling Deployment
- *wecari-ecs-service-php-bg.yaml* - ECS Service for Laravel with Blue/Green Deployment
- *wecari-ecs-deploy-bg.yaml* - Continuous Delivery to ECS for Laravel Project using Blue / Green Deployment
- *wecari-ecs-service-php-efs.yaml* - ECS Service for Laravel with EFS Deployment
- *wecari-ecs-deploy-efs.yaml* - Continuous Delivery for Laravel Project using S3 as source and EFS as destination
- *wecari-kms-key.yaml* - Create KMS Key for Encryption e.g Database Encryption
- *wecari-rds-mysql.yaml* - RDS MYSQL Database
- *wecari-redis.yaml* - Elastic Cache Redis
- *wecari-s3.yaml* - S3 Bucket
- *wecari-cdn-alb.yaml* - Cloudfront Distribution Network with Application Load Balancer as origin
- *wecari-cdn-s3.yaml* - Cloudfront Distribution Network with S3 Bucket as origin (Using S3 Cloudformation Stack)
- *wecari-cdn-s3-bucket.yaml* - Cloudfront Distribution Network with S3 Bucket as origin (using S3 Bucket Name)
- *wecari-vpc-cdn.yaml* - Mechanism to auto restrict connection to VPC to only come from CDN. Use this if you are using Cloudfront and not intending to receive any direct request to either the ALB or Instance
- *wecari-vpc-endpoint-s3.yaml* - VPC Gateway Endpoint (S3). To securely connect endpoints in VPC to S3 via AWS PrivateLink
- *wecari-sqs.yaml* - Create SQS Queue
- wecari-ecs-service-logzio - ECS Service for Logz.io logzio-mysql-logs collector. Used to forward mysql logs to Logz.io