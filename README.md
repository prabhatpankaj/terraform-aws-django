# Terraform AWS Django

## About

This repo is a collection of Terraform modules for deploying Django applications on AWS using EC2, ECS (EC2 + Fargate), and EKS.

Currently this repo contains one high-level module for deploying a Django application on AWS using ECS (EC2 launch type). This is the the root module, but may be moved to another directory in future releases.

See the `examples/simple` directory for an example of how to use this module.

Here is a companion repo that shows how to use this module with a Django application: [https://github.com/briancaffey/django-step-by-step](https://github.com/briancaffey/django-step-by-step).