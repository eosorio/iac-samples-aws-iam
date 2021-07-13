# iac-samples-aws-iam
Infrastructure as Code Sample: AWS IAM

These are sample files for defining policies, roles, key pairs, and other access components managed in IAM.

## Deploying
### In Terraform
* Set your AWS_PROFILE env variable
* Set your AWS keys for that profile
* Fill the values on awsprofile.tfvars
* Terraform validate/plan/apply
```
terraform plan -var-file=awsprofile.tfvars
```
