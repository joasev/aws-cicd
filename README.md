# CI/CD Pipeline with Private AWS Infrastructure

## Overview

This repository provides a comprehensive setup for a CI/CD pipeline using AWS services, ensuring that the entire infrastructure and deployment pipeline remain private within AWS without requiring an internet connection to the outside. The implementation includes the necessary infrastructure setup, deployment configurations, and automation scripts.

## Features

- **CloudFormation Templates**: Includes CloudFormation templates for setting up the EC2 instances, VPC, and networking infrastructure.
- **CI/CD Pipeline Configuration**: Provides a CloudFormation template for configuring the CI/CD pipeline.
- **CodeDeploy Configuration**: Contains the `appspec.yml` file for CodeDeploy configuration.
- **Automated Deployment**: Includes shell scripts for automating the deployment process.
- **Sample Webpage**: The initial state of a sample webpage stored in the source control system.

## Purpose

The primary goal of this project is to establish a CI/CD pipeline that uses AWS services capable of operating entirely within a private VPC. This ensures that the infrastructure and deployment processes do not require an internet connection, enhancing security and compliance for sensitive environments.
