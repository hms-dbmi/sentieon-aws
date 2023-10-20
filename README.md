Launch a VPC with security groups 

```
>>> aws cloudformation create-stack --stack-name sentieon-vpc --template-body file://cloudformation/vpc.yaml --profile 190622331612_AdministratorAccess --region us-east-1
```

Here are [instructions for Sentieon license server](https://support.sentieon.com/appnotes/license_server/#cloud-examples) 