# Azure App Service Gateway Required VNet Integration  Lab 1

This is the first Level 200 lab for Azure App Service Gateway required VNet Integration.

## Scenario:
Unable to perform Gateway Required VNet Integration for the App Service **"AS-N-GWRI-webapp-lab-001-{alias}"**

## Error Message:
![Error](https://github.com/vijaysaayi/Azure-App-Service-Labs/blob/main/Config/VNet%20Integration/Gateway%20Required/Lab%20001%20-%20Unable%20to%20perform%20intergration/Error.png)


## Goal:
Your goal is to ensure that the App Service **"AS-N-GWRI-webapp-lab-001-{alias}"** is able to reach the VM **"AS-N-GWRI-VM-lab-001-{alias}"**. 
When it is working and when we tcpping from Kudu Console to private IP of VM, you see the following response
- Connected to **private IP of VM:443** , time taken: <time in ms>

## Deployment Instructions :
1.	Click on the “Deploy to Azure” button. 
   This will open Custom template deployment page in Azure Portal. <br>
2.	Choose your subscription, create a new resource group, enter your Name/alias and click on "Validate" button. <br>
3.	Click on "Deploy". <br>

## :warning: **Important !!**<br>
> The resources deployed to your subscription would be **chargeable**. Hence ensure that you **delete the resources upon completion** of the lab.<br>
> The screenshot of the **deletion** of Resource Group used by the lab along with you **email address (in screenshot)** should be attached along with you email 

## Deployment Link:
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fvijaysaayi%2FAzure-App-Service-Labs%2Fmain%2FConfig%2FVNet%2520Integration%2FGateway%2520Required%2FLab%2520001%2520-%2520Unable%2520to%2520perform%2520intergration%2Ftemplate.json" target="_blank">
    <img src="https://azurecomcdn.azureedge.net/mediahandler/acomblog/media/Default/blog/deploybutton.png"/>
</a> 

## Resources Created : 
- **Resource  Group**  : To be created
- **App Service**      : AS-N-GWRI-webapp-lab-001-{alias}
- **App Service Plan** : AS-N-GWRI-asp-lab-001-{alias}
- **Virtual Network**  : AS-N-GWRI-VirtualNetwork-lab-001-{alias}
- **Virtual Network Gateway** : AS-N-GWRI-Gateway-lab-001-{alias}
- **Public IP**        : AS-N-GWRI-PublicIP-lab-001-{alias}
- **Virtual Machine**  : AS-N-GWRI-VM-lab-001-{alias}
   







