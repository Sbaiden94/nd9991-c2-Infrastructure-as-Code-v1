## Cloud DevOps Project - C2- Infrastructure as Code - 

### Dependencies
##### 1. AWS account
You would require to have an AWS account to be able to build cloud infrastructure.

##### 2. VS code editor
An editor would be helpful to visualize the image as well as code. Download the VS Code editor [here](https://code.visualstudio.com/download).


### How to run the supporting material?
You can run the supporting material in two easy steps:
```bash
# Ensure that the AWS CLI is configured before runniing the command below
# Create the network infrastructure
# Check the region in the create.sh file
./create.sh myFirstStack Infrastructure_works.yml Infrastructure-parameters.json
# Create servers
# Change the AMI ID
# Check the region in the update.sh file
./update.sh updateStack Infrastructure_works.yml Infrastructure-parameters.json

Final Output of LoadBalancerDNS:
(http://udagr-webse-12qifwtwmexxg-961047690.us-east-1.elb.amazonaws.com/)
```
