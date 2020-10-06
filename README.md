# friendly-carnival
![Packer in Azure](https://github.com/alex-marrero/friendly-carnival/workflows/Packer/badge.svg)

Azure VM Image Automation using Packer 
  - Wwill create an Image for use in Azure on Commits to the Master branch

Will need to add the following Secrets if Repo is Forked

- AZURE_CLIENT_ID - App Registration/ Service Principal with Contributor Access on Subscription
- AZURE_SECRET - Secret for App Registration / Service Principal
- AZURE_RESOURCE_GROUP - Name of RG
- AZURE_SUBSCRIPTION_ID
- AZURE_TENANT_ID


