# A typical AWS network infrastructure

This CloudFormation template helps to create a typical AWS network infrastructure, \
which can be easily deployed as a network base for a typical AWS project.

Run it in AWS CLI as follows:
```
# aws cloudformation create-stack --stack-name MyVPC --template-body file://typical-aws-network.json --parameters ParameterKey=VPCName,ParameterValue="MyVPC"
```
