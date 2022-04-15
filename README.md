# README #
Based on https://cloudonaut.io" templates
## Description
- *alert.yaml*  - SNS Notification for AWS Infrastructure alerts
- *alb.yaml* - Application Load Balance
- *bastion.yaml* - Bastion Host (EC2 Instances in Auto Scaling Group)
- *cdn-alb.yaml* - Cloudfront Distribution Network with Application Load Balancer as origin
- *cdn-s3.yaml* - Cloudfront Distribution Network with S3 Bucket as origin (Using S3 Cloudformation Stack)
- *cdn-s3-bucket.yaml* - Cloudfront Distribution Network with S3 Bucket as origin (using S3 Bucket Name)
- *ecs.yaml* - ECS Cluster of EC2 instances in an Auto Scaling Group
- *ecs-efs.yaml* - ECS Cluster of EC2 instances in an Auto Scaling Group With EFS for Code storage
- *ecs-service.yaml* - ECS Service Rolling Update Deployment
- *ecs-service-php.yaml* - ECS Service for Laravel with Rolling Update Deployment
- *ecs-deploy.yaml* -Continuous Delivery to ECS for Laravel Project using Rolling Deployment
- *ecs-service-php-bg.yaml* - ECS Service for Laravel with Blue/Green Deployment
- *ecs-deploy-bg.yaml* - Continuous Delivery to ECS for Laravel Project using Blue / Green Deployment
- *ecs-service-php-efs.yaml* - ECS Service for Laravel with EFS Deployment
- *ecs-deploy-efs.yaml* - Continuous Delivery for Laravel Project using S3 as source and EFS as destination
- *ecs-service-logzio* - ECS Service for Logz.io logzio-mysql-logs collector. Used to forward mysql logs to Logz.io
- *kms-key.yaml* - Create KMS Key for Encryption e.g Database Encryption
- *rds-mysql.yaml* - RDS MYSQL Database
- *redis.yaml* - Elastic Cache Redis
- *s3.yaml* - S3 Bucket
- *sqs.yaml* - Create SQS Queue- *vpc-cdn.yaml* - Mechanism to auto restrict connection to VPC to only come from CDN. Use this if you are using Cloudfront and not intending to receive any direct request to either the ALB or Instance
- *vpc.yaml* - VPC
- *vpc-endpoint-s3.yaml* - VPC Gateway Endpoint (S3). To securely connect endpoints in VPC to S3 via AWS PrivateLink
- *vpc-nat.yaml* - NatGateway in VPC
- *vpc-nat-instance.yaml* - VPC: NAT Instance in an Auto Scaling Group