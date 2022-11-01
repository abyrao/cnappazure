# cnappazure

CNAPPAZURE Repo

Create Service Principal with Client Secret  (this has already been completed but the documentation is for future use)

https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/guides/service_principal_client_secret


Add the below variables to your Terraform Cloud workspace

Go to https://developer.hashicorp.com/terraform/tutorials/cloud-get-started/cloud-create-variable-set for more information

ARM_CLIENT_ID = This is the Application (client) ID of the Service Principal
ARM_CLIENT_SECRET = This is the secret password for the Service Principal
ARM_TENANT_ID = This is the Directory (tenant) ID of the Service Principal
ARM_SUBSCRIPTION_ID = The ID of the Subscription where resources will be create

Change Resource Group name to your user name or first part of your email address

Change the Resource Group name by replacing the "yourusernameforresourcegroup" in main.tf (line 18 of code).