# Terraform: Deploy A Three-Tier Architecture in AWS

# Objective
The objective of this project is to design a secure infrastructure for a 3-tier architecture and use terraform(infrastructure as code) to spin it all up on AWS.

# Project infrastructure
* `main` branch: To deploy a Three-Tier Architecture in AWS Cloud

# Prerequisites
1. Install Terraform
2. Install the AWS CLI
3. Sign up for an AWS Account
4. Your preferred IDE (I used Visual Studio Code)

# How this works
1. [`terraform`](terraform) --> run below tf commands to setup Three-Tier Architecture
      * terrform init --> This command download the plugin for required provider which we mention terraform file
      * terrform plan --> It won't create any infrasture , it will show what actually it is going to create.
      * terraform apply --> To create resouces
