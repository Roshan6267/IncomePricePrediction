### End to End ML Project

### created a environment
```
conda create -p income python==3.8

conda activate income/
```
### install all necessary libraries
```
pip install -r requirements.txt
```
### Dockerfile setup 
```
docker build -t incomeprediction:latest .
```

```
1. Docker Build checked
2. Github Workflow
3. Iam User In AWS
```
### Docker Setup In EC2 commands to be Executed

```

#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp 
```
#### Configure EC2 as self-hosted runner:

### Setup github secrets:

```
AWS_ACCESS_KEY_ID 

AWS_SECRET_ACCESS_KEY

AWS_REGION 

AWS_ECR_LOGIN_URI 

ECR_REPOSITORY_NAME 
```