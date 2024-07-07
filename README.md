# End to end Text-summarization-Project

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update configuration manager in src config
5. Update the components
6. Update the pipeline
7. Update the main.py
8. Update the app.py


# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/Chetan2407/Text-summarization-Project
```

### STEP 01- Create a conda environment after opening the repository

### STEP 02- install the requirements

```bash
open up your local host and port
```
```bash
Author: Chetan Raj
Data Scientist
Email: chetanrajmota@gmail.com
```

# AWS-CICD-Deployment-with Github-Actions

## 1. Login to AWS console

## 2. Create I AM user for deployment

    #with specific access
    1. EC2 access : It is virtual machine
    2. ECR: Elastic Container registry to save your docker image in aws


    #Description: About the deployment

    1. Build docker image of the source  code
    2. Push your docker image to ECR
    3. Launch your EC2
    4. Pull your image from ECR in EC2
    5. Launch your docker image in EC2

    #Policy:

    1. AmazonEC2ContainerRegistryFullAccess
    2. AmazonEC2FullAccess


## 3. Create ECR repo to store/save docker image
   - save the URI: public.ecr.aws/v4v4w0t1/text-s
## 4. Create EC2 machine
