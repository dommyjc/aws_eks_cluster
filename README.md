# Deploy EKS Cluster in AWS
This is to deploy a EKS cluster in AWS

## Prequisites:
- Need to have AWS CLI installed in order to login to AWS via command line (as per below instructions).

- Configure Environment Variables for AWS Access
    - export AWS_ACCESS_KEY_ID=<your-access-key>
    - export AWS_SECRET_ACCESS_KEY=<your-secret-access-key>
    - export AWS_DEFAULT_REGION=ap-southeast-2
    - export AWS_DEFAULT_OUTPUT=json

-  Provision the AKS cluster via terraform
    - terraform init
    - terraform plan
    - terraform apply