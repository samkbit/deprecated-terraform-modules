# Terraform modules #
Various terraform modules as __ZIP__ archives. 

Terraform understands this format so all you have to do is specify the URL in ```source``` of the __module__ block.

```terraform
module "service_azure_devops_agent_on_ec2" {
  source = "url/to/zip-file"
  
  # ...
```
