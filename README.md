# Terraform modules #

## All of my Terraform Links ##
I do much of AWS (or other cloud) resource management using __Terraform__ so be sure to refer to my links below.
   * [Terraform Central Starting Point Documentation](https://github.com/samkbit/frequently-used-cicd-scripts-tools-and-commands/tree/master/terraform): Central starting documentation.
   * Provider Specific
      * [Terraform Modules For AWS Documentation](https://github.com/samkbit/cd-terraform-modules-aws): These are descriptions and details on my collection of re-usable modules for use with provider AWS.
   * [Terraform Modules as ZIP Files](https://github.com/samkbit/terraform-modules): These are my collection of live and re-usable modules that can be consumed by any Terraform configuration.
   * [Terraform Live Modules](https://github.com/samkbit/cd-terraform-live): These are modules to help recreate resources for a given org in a given environment.
See [My Central Starting Point Documentation on Terraform](https://github.com/samkbit/frequently-used-cicd-scripts-tools-and-commands/blob/master/terraform/README.md)

## This Repo: Terraform Modules as ZIP Files ##
Various terraform modules as __ZIP__ archives. 

Terraform understands this format so all you have to do is specify the URL in ```source``` of the __module__ block.

```terraform
module "service_azure_devops_agent_on_ec2" {
  source = "url/to/zip-file"
  
  # ...
```
