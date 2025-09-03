# JFrog Infrastructure as Code Demo

This repository contains a hello world example which demonstrates the Terraform features of JFrog Infrastructure as code. In particular:

## JFrog CLI

After installing the JFrog CLI, you will then have the capability of scanning your IaC projects locally. 

For this example repository, you will first need to pull down the code base to your local enviornment.

Terraform is not required to be installed for any of the following examples.

Once in your cloned directory, you can run `jf audit -- iac` which will recursively identify any of the `.tf` files in the directory.

