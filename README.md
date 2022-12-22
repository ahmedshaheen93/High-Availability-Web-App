# High-Availability-Web-App
Deploy a High-Availability Web App using Cloud Formation

1- Create network stack with the following command
```bash
aws cloudformation create-stack --stack-name network --template-body file://network.yaml  --parameter file://network-prams.json --profile IaC
```

