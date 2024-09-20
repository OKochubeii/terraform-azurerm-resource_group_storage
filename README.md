# terraform-azurerm-resource_group_storage
This repository is created for mate task 6

module "resource_group_storage" {
  source = "github.com/OKochubeii/terraform-azurerm-resource_group_storage"

  resource_group_name   = "example-resources"
  location              = "Poland Central"
  storage_account_name  = "storageaccountname"
}
