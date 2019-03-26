# terraform-deploy-template

## Requirements
* Git
* Packer
* Terraform

## ENV Variables

* AWS_ACCESS_KEY_ID
* AWS_SECRET_ACCESS_KEY

## Usage

Use this repo as a template for creating new terraform deployment scripts.
The Makefile is where one defines actions, and from there we can set what actions are available for the deployment.  
This example Makefile covers most of the actions one might need.

## TODO
** Integrate some kind of automated lookup of aws credentials via 'vault' or some other EKV service
** Add an example workflow to include all possible action combinations.

# This repo is based on:

https://groups.google.com/forum/#!msg/terraform-tool/7Gdhv1OAc80/iNQ93riiLwAJ
