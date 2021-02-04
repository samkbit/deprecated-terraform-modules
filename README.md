# Terraform modules #
See [My Central Starting Point Documentation on Terraform](https://github.com/samkbit/frequently-used-cicd-scripts-tools-and-commands/blob/master/terraform/README.md)

Various terraform modules as __ZIP__ archives. 

Terraform understands this format so all you have to do is specify the URL in ```source``` of the __module__ block.

```terraform
module "service_azure_devops_agent_on_ec2" {
  source = "url/to/zip-file"
  
  # ...
```
