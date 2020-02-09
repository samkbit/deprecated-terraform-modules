# Terraform modules #
Various terraform modules as __ZIP__ archives. Terraform understands this format so all you have to do is specify the URL in ```source``` of the __provider__ block as follows.

```terraform
module "service_azure_devops_agent_on_ec2" {
  source = "../../../modules/services/azure-devops-agent-on-ec2/v0.0.1"
  
  # ...
```
