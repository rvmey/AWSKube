# AWSKube
Single-node AWS EC2 Kubernetes cluster cloudformation template

Change the KeyName value in the params.json to your own [key pair stored in AWS](https://console.aws.amazon.com/ec2), then run this:
```
aws configure
aws cloudformation create-stack --stack-name myk8s --template-body file://single-node-k8s.cf --parameters file://params.json
```