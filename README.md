# AWS Network Infrastructure Template

This CloudFormation template creates network infrastructure for a typical AWS project:<br>
* 2 public and 2 private subnets
* all subnets have Internet access


Just run:
```
# aws cloudformation create-stack --stack-name MyVPC --template-body file://aws-network-template.json --parameters ParameterKey=VPCName,ParameterValue="MyVPC"
```
