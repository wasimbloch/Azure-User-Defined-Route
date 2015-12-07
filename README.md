# Azure-User-Defined-Route
Azure User Defined Route

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fwasimbloch%2FAzure-User-Defined-Route%2Fmaster%2FDeploymentTemplate.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template allows you to create a User Defined Route (UDR) with three virtual machine, three NIC, default NSG with Virtual Network and Routing Table.
This teamplte will create Routing rule for the Virutal Appliance as Next hope type.

Below are the parameters that the template expects.

| Name   | Description    |
|:--- |:---|
| LOCATION | Location for the deployment |
| NEWSTORAGEACCOUNTNAME | name of the standard storage account, defaults to Standard_LRS |
| ADMINUSERNAME | Admin user Name for the RDP to VMs |
| ADMINPASSWORD | Admin Password for the RDP to VMs |
| UNIQUEDNSPREFIXFORVM | Address prefix for the Virtual Network specified in CIDR format |
| VMNAMEPREFIX | Address prefix for the Virtual Machine |
| PUBLICIPADDRESSTYPE | Public IP Address - use default value |
| WINDOWSOSVERSION | Windows OS version - use default value |
