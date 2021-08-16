# git-actions-az-deploy-demo
[![Deploy Action status](https://github.com/sbartholomeusz/git-actions-az-deploy-demo/workflows/azure-deploy/badge.svg)](https://github.com/sbartholomeusz/git-actions-az-deploy-demo/actions)

![Banner](/docs/git-repo-banner.png?raw=true "")

# Overview
Demonstration of how to deploy Azure Functions using Github Actions.

The code contained in this repository relates to the following blog article:</br>
https://www.shanebart.com/deploy-az-func-with-github-actions/

# Processing
The `.github/workflows/deploy-to-azure.yml` file triggers an automated deployment upon changes being 'pushed' to the `master` branch of this repository.
</br></br>
The deployment workflow does the following:
1. Creates the Azure Function App resource
2. Builds the Azure Function C# project
3. Deploys the Azure Function code
