# git-actions-az-deploy-demo
[![Deploy Action status](https://github.com/sbartholomeusz/git-actions-az-deploy-demo/workflows/azure-deploy/badge.svg)](https://github.com/sbartholomeusz/git-actions-az-deploy-demo/actions)

![Banner](/docs/git-repo-banner.png?raw=true "")

# Overview
Demonstration of how to deploy Azure Functions using Github Actions.

The `.github/workflows/deploy-to-azure.yml` file triggers an automated deployment upon changes being 'pushed' to the `master` branch of this repository.

# Processing
The deployment workflow does the following:
1. Create the Azure Function App
2. Build the Azure Function C# project
3. Deploy the code to the Azure Function App
