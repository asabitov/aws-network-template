# A typical AWS network infrastructure

This CloudFormation template helps to create a typical AWS network infrastructure, which can be used as an easy deployable network base for various projects. 

Run it in AWS CLI as follows:
```
# aws cloudformation create-stack --stack-name MyVPC --template-body file://typical-aws-network.json --parameters ParameterKey=VPCName,ParameterValue="MyVPC"
```
