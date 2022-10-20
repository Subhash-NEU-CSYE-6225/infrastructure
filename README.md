# infrastructure

aws cloudformation create-stack --stack-name myvpcwithparam --template-body file://CloudFormation/csye6225-infra.yaml --parameters ParameterKey=VpcCidrBlock,ParameterValue="10.1.1.0/24" ParameterKey=RouteTableName,ParameterValue="myRouteTable" ParameterKey=Subnet1Name,ParameterValue="mySubnet1" ParameterKey=VpcCidrBlock,ParameterValue="10.1.1.0/24" ParameterKey=Subnet2Name,ParameterValue="mySubnet2" ParameterKey=Subnet3Name,ParameterValue="mySubnet3" ParameterKey=Subnet1CidrBlock,ParameterValue="10.0.0.0/24" ParameterKey=Subnet2CidrBlock,ParameterValue="10.0.0.0/32" ParameterKey=Subnet3CidrBlock,ParameterValue="10.0.0.0/40" ParameterKey=Subnet1AvailabilityZone,ParameterValue="us-east-1a"
ParameterKey=Subnet2AvailabilityZone,ParameterValue="us-west-2a"
ParameterKey=Subnet3AvailabilityZone,ParameterValue="us-west-2b"