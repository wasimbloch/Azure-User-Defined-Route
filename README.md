# Azure-User-Defined-Route
Azure User Defined Route

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fwasimbloch%2Fazure-arm-nsg%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template allows you to create a User Defined Route (UDR) with three virtual machine, three NIC, default NSG with Virtual Network and Routing Table.
This teamplte will create Routing rule for the Virutal Appliance as Next hope type.

Below are the parameters that the template expects.

| Name   | Description    |
|:--- |:---|
| location | Location for the deployment |
| newStorageAccountName | name of the standard storage account, defaults to Standard_LRS |
| adminUsername | Admin user Name for the VMs |
| uniqueDnsPrefixForVM | Address prefix for the Virtual Network specified in CIDR format |
| vmNamePrefix | Address prefix for the Virtual Machine |
