# Azure ARM Template for IIS with Web Deploy

This resource manager template deploys an IIS server running on an Azure VM. The VM is bootstrapped with a PowerShell DSC configuration located in this repo. The DSC config will install and configure IIS, ASP.NET, and create a default website. Additionally, the DSC config installs and configures the Web Deploy service so you can easily deploy code to the server from Visual Studio.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmikepfeiffer%2Fiis-webdeploy%2Fmaster%2Fazuredeploy.json" target="_blank"><img src="http://azuredeploy.net/deploybutton.png"/></a>
