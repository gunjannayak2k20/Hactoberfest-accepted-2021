# Hactoberfest-accepted-2021


Terraform introduction

Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently. Terraform can manage existing and popular service providers as well as custom in-house solutions.

AWS authentification

The AWS provider is used to interact with the many resources supported by AWS. The provider needs to be configured with the proper credentials before it can be used.

provider "aws" {
  access_key = "secret"
  secret_key = "secret"
  region     = "us-east-1"
}

Getting Started

Before terraform apply you must download provider plugin:

terraform init
Display plan before apply manifest

terraform plan
Apply manifest

terraform apply
Destroy stack

terraform destroy

This repo inculdes simple ec2 provision on aws by Terraform template.
