#Cincy Azure Bootcamp - Azure Resource Manager HOL
These hands-on labs are designed to help you get familiar with Azure Resource Manager.

#Prerequisites
Before you can complete the labs you need a few things (note you can use either PowerShell or Xplat-CLI)
- [Azure PowerShell](https://github.com/Azure/azure-powershell/releases)
- [Microsoft Azure Xplat-CLI](https://github.com/Azure/azure-xplat-cli/releases)
- [An Azure Subscription](https://azure.microsoft.com/) (a trial account is fine)
- [Visual Studio Code](https://code.visualstudio.com/) (or another text editor capable of highligting JSON, for you own sake don't use notepad)

#The structure
The labs are organized in steps. The steps are meant to be completed from the first to the last. Each step contains a readme.md file that describes what the step is about, and two folders:
- begin
- complete

The begin folder contains a starting template that can be used to help you get started. The template contains comments // sometimes with links to help you along.

If you get stuck or just want inspiration the complete folder contains one possible solution to the task. 

Please note that if you try to run the complete solution with the provided *.param.json files you might encounter errors if other people have deployed resources with the same names, so you should always update the names to be unique.  

##Two labs
This hands on sessions consists of two labs
- [Azure Web Apps](lab1-azure-webapps/readme.md)
- [Azure Virtual Machines](lab2-azure-virtualmachines/readme.md)

Content based on (https://github.com/sjkp/azure-arm-hol)
 

