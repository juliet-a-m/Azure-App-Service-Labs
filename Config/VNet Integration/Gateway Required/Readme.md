# Azure App Service Gateway Required VNet Integration  Lab 1

This is a Level 200 lab for Azure App Service built-in authentication aka Azure EasyAuth  

## Scenario:
In this lab, you will need to find out the why tcpping from App Service to the VM "" fails and fix it. 
When it is working, when we tcpping from Kudu Console, you see the following response
- Connected to <private IP of VM>:443, time taken: <time in ms>

## Goal:
Your goal is to ensure that the App Service "" is able to reach the VM "". 

## Deployment Instructions :
1.	Click on the “Deploy to Azure” button. 
   This will open a new browser window and navigate to the Azure Deployment Page. <br>
2.	Choose your subscription, enter your subscription ID and click on "Validate" button. <br>
3.	Click on "Deploy". <br>

## Deployment Link:
<a href="https://raw.githubusercontent.com/vijaysaayi/Azure-App-Service-Labs/main/Config/VNet%20Integration/Gateway%20Required/template.json" target="_blank">
    <img src="https://azurecomcdn.azureedge.net/mediahandler/acomblog/media/Default/blog/deploybutton.png"/>
</a> 

## Resources Created : 
- Resource  Group  : Azure_App_Service_Labs-<alias>
- App Service      : Azure_App_Service_Labs-<alias>







