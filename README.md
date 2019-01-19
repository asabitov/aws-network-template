# AWS network infrastructure template

This CloudFormation template easily creates network infrastructure for a typical AWS project.

Just run:
```
# aws cloudformation create-stack --stack-name MyVPC --template-body file://typical-aws-network.json --parameters ParameterKey=VPCName,ParameterValue="MyVPC"
```
