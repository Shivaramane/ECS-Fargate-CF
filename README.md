# ECS-Fargate-CF

ECS-NetworkStack.yml is the main Cloudformation template to create the VPC and other networking services.
ECS-ServiceStack.yml utilizes this parent stack export values and creates an ECS Fargate cluster services.
