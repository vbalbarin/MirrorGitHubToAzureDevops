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

## Contribute
TODO: Explain how other users and developers can contribute to make your code better. 

If you want to learn more about creating good readme files then refer the following [guidelines](https://docs.microsoft.com/en-us/azure/devops/repos/git/create-a-readme?view=azure-devops). You can also seek inspiration from the below readme files:
- [ASP.NET Core](https://github.com/aspnet/Home)
- [Visual Studio Code](https://github.com/Microsoft/vscode)
- [Chakra Core](https://github.com/Microsoft/ChakraCore)