# CloudFormation Templates
A place to store the AWS CloudFormation templates which constitute gavin-tech.com

# Steps to create site
1. Run vpc.yml
1. Run ecr.yml
1. Create IAM user with programmatic access and push Docker images.
1. Create persistent (non-CF) resources:
    * Key pair
    * Elastic IP
    * EBS volume for Docker bind mounts
    * S3 bucket for Docker bind mounts
1. Run ecs.yml
1. Update DNS
