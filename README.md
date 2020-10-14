# Introduction

Launching a container in AWS ECS.

## Getting started

- Create AWS ECR repository `ecs-demo/nodejs-sample`.
- Login with `docker` to the AWS repository.
- Build and push Docker image to the AWS repository.
- Create EC2 security group that allows traffic on port `3000` as defined in the `Dockerfile` and the NodeJS code.
- Create Cluster, Task Definition and Service.
- Access service via public IP address of the Task Definition on port `3000`.

