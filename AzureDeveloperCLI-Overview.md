# Azure Developer CLI Overview

## What is Azure Developer CLI?

- A developer CLI that accelerates the time it take for you to get started on Azure. The Azure Developer CLI (azd) provides a set of developer-friendly commands that map to key stages in your workflow - code, build, deploy, monitor, repeat.

## Installation

- You can install via powershell command ``powershell -ex Allsigned -c "Invoke-RestMethod 'https://aka.ms/install-azd.ps1' | Invoke-RestExpression"

## Basic Commands

- ``azd --version`` - Displays version information
- ``azd --help`` - Print usage information
- ``azd login`` - Login to Azure
- ``azd logout`` - Log out from Azure
- ``azd template list`` - Manage templates
  - ``azd template --help`` - Print usage information about templates

## Sandbox

- ``azd init --help`` - Print usage information
- ``azd init --template todo-nodejs-mongo`` - Initialize locally
- ``azd up --template todo-nodejs-mongo`` - deploy directly

- ``azd provision --help`` - Print usage information


## Tips

- you can clone repeo from <https://github.com/Azure/azure-dev>
- documentation is located at <https://learn.microsoft.com/en-us/azure/developer/azure-develper-cli/overview>
- if you save your files with .azcli extension you can run commands via right-clicking on them
- if you are using visual studio code you can install 'Azure Developer CLI' extension (by Microsoft)

