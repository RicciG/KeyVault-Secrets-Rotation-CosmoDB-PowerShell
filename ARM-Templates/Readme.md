# CosmosDB keys rotation ARM templates

This template creates below components to help demonstrate CosmosDB keys rotation in Key Vault using Function and Event Grid notification.

### CosmosDB keys rotation functions ARM template:

Components:

- App Service Plan
- Function App with access to Key Vault and CosmosDB 
- Functions to rotate CosmosDB keys
- Event Subscription
- Secret deployment (optional)

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/RicciG/KeyVault-Secrets-Rotation-CosmoDB-PowerShell/main/ARM-Templates/Function/azuredeploy.json" 
target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>
<a href="http://armviz.io/#/?load=https://raw.githubusercontent.com/RicciG/KeyVault-Secrets-Rotation-CosmoDB-PowerShell/main/ARM-Templates/Function/azuredeploy.json" 
target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png"/>
</a>

### Event subscription for existing CosmosDB keys rotation function ARM template

Components:

- Event Subscription
- Access for Function to access CosmosDB keys
- Secret deployment (optional)

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/RicciG/KeyVault-Secrets-Rotation-CosmoDB-PowerShell/main/ARM-Templates/Add-Event-Subscription/azuredeploy.json"
target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>
<a href="http://armviz.io/#/?load=https://raw.githubusercontent.com/RicciG/KeyVault-Secrets-Rotation-CosmoDB-PowerShell/main/ARM-Templates/Add-Event-Subscription/azuredeploy.json"
target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png"/>
</a>

If you are new to the template development, see:

- [Azure Resource Manager documentation](https://docs.microsoft.com/en-us/azure/azure-resource-manager/)
- [Use Azure Key Vault to pass secure parameter value during deployment](https://docs.microsoft.com/azure/azure-resource-manager/resource-manager-keyvault-parameter)
- [Tutorial: Integrate Azure Key Vault in Resource Manager Template deployment](https://docs.microsoft.com/azure/azure-resource-manager/resource-manager-tutorial-use-key-vault)

Tags: Azure Key Vault, Key Vault, Resource Manager, Resource Manager templates, ARM templates
