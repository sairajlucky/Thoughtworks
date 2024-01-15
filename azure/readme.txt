to deploy the kubernetes please run this command.

Connect-AzAccount
Set-AzContext -subscriptionName <subscriptionName>
az deployment group create --resource-group twdemo --template-file .\aks.json --parameters .\aks-param.json