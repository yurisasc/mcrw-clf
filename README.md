---
title: Scenery
emoji: 🚀
colorFrom: pink
colorTo: red
sdk: gradio
sdk_version: 3.19.1
app_file: app.py
pinned: false
license: apache-2.0
---

# Serverless Minecraft/Real world classifier

This is an example of how to deploy a serverless machine learning application with Gradio and AWS Lambda.


## Local Development

1. Install dependencies

```bash
pip install -r requirements.txt
```

2. Run the application

```bash
python app.py
```

## Deploying to AWS Lambda

1. install the AWS CDK CLI

```bash
npm install -g aws-cdk
```

2. Install dependencies

```bash
pip install aws-cdk-lib constructs
```

3. Boostrap and deploy project in the cloud
```
cdk bootstrap && cdk deploy
```

To remove the deployed stack, run the following command:

```bash
cdk destroy
```
