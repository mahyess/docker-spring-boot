# Amazon ECR Docker Helper 

![Amazon ECR logo](docs/ecr.png "Amazon ECR")


The Amazon ECR Docker Credential Helper is a
[spring boot docker 
repo](https://github.com/mahyess/docker-spring-boot)
for the Docker daemon that makes it easier to use
[Amazon Elastic Container Registry](https://aws.amazon.com/ecr/).

## Prerequisites

You must have at least Docker 1.11 installed on your system.

You also must have AWS credentials available.  See the [AWS credentials section](#aws-credentials) for details on how to
use different AWS credentials.

Build 
`docker build -t ecs-boot-repo .`

Tag it
`docker tag docker-spring-boot:latest 
195916980817.dkr.ecr.us-east-1.amazonaws.com/docker-spring-boot:latest`

Push the image
`docker push 
195916980817.dkr.ecr.us-east-1.amazonaws.com/docker-spring-boot:latest`
