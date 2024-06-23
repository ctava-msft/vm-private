---
description: This template deploys a linux vm.
page_type: sample
products:
- azure
- azure-resource-manager
urlFragment: vm-private
languages:
- bicep
- json
---
# Azure VM Setup

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fctava-msft%2Fvm-private%2Fmain%2Fazuredeploy.json)



This template sets up Azure VM.

## Resources

The following table describes the resources created in the deployment:

| Provider and type | Description |
| - | - |
| `Microsoft.Compute` | `An Azure VM Compute` |

## Commands to generate files from main.bicep:

```
bicep build main.bicep --outfile azuredeploy.json
```

## Learn more

If you are new to Azure virtual machines, see:

- [Azure Virtual Machines](https://azure.microsoft.com/services/virtual-machines/).
- [Azure Virtual Machines documentation](https://learn.microsoft.com/azure/virtual-machines/)
- [Template reference](https://learn.microsoft.com/azure/templates/microsoft.compute/allversions)
- [Quickstart templates](https://learn.microsoft.com/en-us/samples/browse/?expanded=azure&products=azure-resource-manager)

If you are new to template deployment, see:

- [Azure Resource Manager documentation](https://learn.microsoft.com/azure/azure-resource-manager/)
- [Quickstart: Create an Ubuntu Linux virtual machine using an ARM template](https://learn.microsoft.com/azure/virtual-machines/linux/quick-create-template)

`Tags: Azure4Student, virtual machine, Linux, Ubuntu Server, Beginner, Microsoft.Network/networkInterfaces, Microsoft.Network/networkSecurityGroups, Microsoft.Network/virtualNetworks, Microsoft.Network/virtualNetworks/subnets, Microsoft.Network/publicIPAddresses, Microsoft.Compute/virtualMachines`
