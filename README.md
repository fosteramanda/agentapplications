# Agent Applications and Deployments Bug Bash

## Important Testing Information
- Test in canary (eastus2euap) and westus2
- Use an allowlisted subscription
- Use API Version 10-01-2025-preview

## Get Access Token
The simplest way to get a bearer token is to use Azure CLI. From command prompt run: 
- az login
- az account get-access-token

## REST API Testing in VSCode
- Clone this repo and open in VS Code
- Install the [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
- Open the .http file in VSCode
- Replace the variables (@variable_name) with appropriate values
