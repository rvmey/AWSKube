# AWSKube
Single-node AWS EC2 Kubernetes cluster cloudformation template

Run this:
```
aws configure
aws cloudformation create-stack --stack-name myk8s --template-body file://single-node-k8s.cf --parameters file://params.json
```