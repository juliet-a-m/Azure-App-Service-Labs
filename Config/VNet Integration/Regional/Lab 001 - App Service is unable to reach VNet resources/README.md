# Azure App Service Regional VNet Integration  Lab 1

This is the first Level 200 lab for Azure App Service Regional VNet Integration.

## Scenario:
Unable to reach the VM "**AS-N-RegInt-VirtualMachine-lab-001-{alias}**" in the Virtual Network "**AS-N-RegInt-VirtualNetwork1-lab-001-{alias}**".

## Goal:
Your goal is to ensure that the App Service **"AS-N-RegInt-webapp-lab-001-{alias}"** is able to reach the VM **"AS-N-RegInt-VirtualMachine-lab-001-{alias}"**. 
When it is working and when we tcpping from Kudu Console to private IP of VM, you see the following response
- Connected to **private IP of VM:443** , time taken: <time in ms>

## Deployment Instructions :
1.	Click on the **“Deploy to Azure”** button. 
   This will open Custom template deployment page in Azure Portal. <br>
2.	Choose your subscription, create a new resource group, enter your Name/alias. <br>
3.	Click on **"Review and Create"**. <br>

## :warning: **Important !!**<br>
> The resources deployed to your subscription would be **chargeable**. Hence ensure that you **delete the resources upon completion** of the lab.<br>
> The screenshot of the **deletion** of Resource Group used by the lab along with you **email address (in screenshot)** should be attached along with you email 

## Deployment Link:
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fvijaysaayi%2FAzure-App-Service-Labs%2Fmain%2FConfig%2FVNet%2520Integration%2FRegional%2FLab%2520001%2520-%2520App%2520Service%2520is%2520unable%2520to%2520reach%2520VNet%2520resources%2Ftemplate.json" target="_blank">
    <img src="https://azurecomcdn.azureedge.net/mediahandler/acomblog/media/Default/blog/deploybutton.png"/>
</a> 

## Resources Created : 
- **Resource  Group**  : To be created
- **App Service**      : AS-N-RegInt-webapp-lab-001-{alias}
- **App Service Plan** : AS-N-RegInt-asp-lab-001-{alias}
- **Virtual Network1**  : AS-N-RegInt-VirtualNetwork1-lab-001-{alias}
- **Virtual Network2**  : AS-N-RegInt-VirtualNetwork2-lab-001-{alias}
- **Virtual Machine**  : AS-N-RegInt-VirtualMachine-lab-001-{alias}









