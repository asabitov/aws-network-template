# A typical AWS network infrastructure

This CloudFormation template creates network infrastructure for a typical AWS project.

Run:
```
# aws cloudformation create-stack --stack-name MyVPC --template-body file://typical-aws-network.json --parameters ParameterKey=VPCName,ParameterValue="MyVPC"
```
