# Mirroring Github Repository to Azure Devops Repository

## Introduction 
This sample code uses an Azure Devops pipeline to mirror a Github repository to an Azure Devops repository.

![Architecture](./assets/arch.png)

## Getting Started

Requirements:

1. Azure Devops Organization
    * Target repository
    * Pipeline repository
    * This code

2. GitHub Personal Account or Organization
    * Source repository
    * Azure Pipeline application (TODO: Check if required for a public repo)
    * Github User that has access to personal account or organization

Create an Azure DevOps Organization.
Create a new Project.
Create a new repository named `MirrorGitHubToAzureDevops`.
Import this GH repository into `MirrorGitHubToAzureDevops`.
Create a new repository to hold the mirrored GH repository `<name_of_gh_repo>`
Import GH repository.
Allow build service to create pull requests to the mirrored repository.
Create DevOps Pool.

## Appendix

```bash
az extension add --name azure-devops

repo='MirrorGitHubToAzureDevops'
project='<name_of_project>'
org='<url_of_devops_org>'

az repos create --org "${org}" --project "${project}" --name "${repo}"
```