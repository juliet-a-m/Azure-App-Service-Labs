# Azure App Service Regional VNet Integration  Lab 1

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
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fvijaysaayi%2FAzure-App-Service-Labs%2Fmain%2FConfig%2FVNet%2520Integration%2FRegional%2FLab%2520001%2520-%2520App%2520Service%2520is%2520unable%2520to%2520reach%2520VNet%2520resources%2Ftemplate.json" target="_blank">
    <img src="https://azurecomcdn.azureedge.net/mediahandler/acomblog/media/Default/blog/deploybutton.png"/>
</a> 

## Resources Created : 
- Resource  Group  : Azure_App_Service_Labs-<alias>
- App Service      : Azure_App_Service_Labs-<alias>







