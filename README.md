# Terraspace AWS EC2 Example

This project shows how to use the [AWS EC2 Instance Terraform registry module](https://registry.terraform.io/modules/terraform-aws-modules/ec2-instance/aws) with [Terraspace](https://terraspace.cloud/).

* Thanks and credit goes to the author of this module: Anton B.
* Most contributors are doing this on their own free time. Please support them. Contribute back and send them a pull request. Some may ask for donations. Donate to them. Some are consultants. Hire them.

## Setup

    git clone https://github.com/boltops-tools/terraspace-aws-ec2
    cd terraspace-aws-ec2
    bundle

## Deploy

To deploy:

    terraspace up basic

This deploys four ec2 instances to the `eu-west-1` Ireland region:

* example-network
* example-normal
* example-t2-unlimited
* example-t3-unlimited

## Updating

To update the modules to the latest version from the Terraform registry.

    terraspace bundle update

## More Examples

    $ terraspace list
    app/stacks/basic
    app/stacks/volume-attachment

## About

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

[Terraspace](https://terraspace.cloud/) and this project was built by [BoltOps](https://www.boltops.com). We also offer:

* [Paid Consulting Services](https://www.boltops.com/consulting)
* [BoltOps Pro: Infrastructure Code as a Service](https://www.boltops.com/pro)
