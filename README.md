# Jenkins AMI Creation with Packer

This is a simple setup to create an AMI to deploy Jenkins.  

## Requirements

+ packer
+ aws-cli

## How to use

1.  Open packer.json, and change the profile to match your AWS CLI profile.  (If you don't have multiple, it should be `default`
2.  Run `packer build packer.json`
