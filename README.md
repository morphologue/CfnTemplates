# CloudFormation Templates
A place to store the AWS CloudFormation templates which constitute gavin-tech.com

# Steps to create site
1. Get SMTP credentials from AWS SES and substitute into Exim smarthost configs.
1. Create Elastic IP.
1. Run vpc.yml
1. Run ecr.yml
1. Push Docker images.
1. Run docker.yml