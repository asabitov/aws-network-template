# AWS Network Infrastructure Template

This CloudFormation template easily creates network infrastructure for a typical AWS project.

Just run:
```
# aws cloudformation create-stack --stack-name MyVPC --template-body file://aws-network-template.json --parameters ParameterKey=VPCName,ParameterValue="MyVPC"
```
