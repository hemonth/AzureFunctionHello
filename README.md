# AzureFunctionHello

Project skeleton 
Application folder contains various files for the project, including configurations files named local.settings.json and host.json. 
Because local.settings.json can contain secrets downloaded from Azure, the file is excluded from source control by default in the .gitignore file.

Run the app you need Java 8 (Note: Azure Functions does not support Java11 as of 2019)
Command: mvn azure-functions:run

