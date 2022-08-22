# Overview
This is a second Project of the Udacity Devops training: Building a CI/CD Pipeline
A summary of the Task Performed in this project include:
- Using Github actions with Makefile and requirement.txt
- Using Application code to perform initial lint, test and install cycle
- intergration of the Project with Azure Pipeline to enable continuous Delivery to Azure App Service


# Project Plan
## Project Spreadsheet
This Spreadsheet shows a detailed weekly, quarterly and Yearly plan for the Project.
[Spreadsheet link](https://docs.google.com/spreadsheets/d/1xy7B-lyBBW9qWSJhsjvouWkt3abNHoRkGnAv9fvSJII/edit#gid=1348135932)
## Trello Board
This Trello Board shows a simple work flow of To-dos, In-Progress and Completed Project Tasks
[Trello link](https://trello.com/b/UZPqIj7M/project2-azure-devops-training)


# Achitectural Diagram
This shows the key parts of the System work

# CI: Set Up Azure Cloud Shell
## Creating a Makefile, Requirements.txt and Virtual Environment
I created a Makefile, requirements.txt in Azure cloud Shell and added the codes shown in the screenshot shown below and saved
![screenshot](https://github.com/Uchejen/Project2-azure-cloud-shell/blob/main/Screenshots/MAkefile_command.JPG?raw=true)
![screenshot](https://github.com/Uchejen/Project2-azure-cloud-shell/blob/main/Screenshots/Requriements.JPG?raw=true)

Also, the code shown below was used to create a Python Vurtual Environment. Run the following command ...
![screenshot1](https://github.com/Uchejen/Project2-azure-cloud-shell/blob/main/Screenshots/virt_env.JPG?raw=true)

## Project Cloned Into Azure Cloud Shell
This screenshot shows the cloning of the repo into Azure cloud shell
![screenshot1](https://github.com/Uchejen/Project2-azure-cloud-shell/blob/main/Screenshots/repo_clone.JPG?raw=true)

## Local test
The two screenshots below shows how the project script and the test script were created. it also shows how the make all command was run and the ouput of the test
![screenshot1](https://github.com/Uchejen/Project2-azure-cloud-shell/blob/main/Screenshots/Makefile1.JPG?raw=true)
![screenshot1](https://github.com/Uchejen/Project2-azure-cloud-shell/blob/main/Screenshots/Makefile2.JPG?raw=true)

# CI: Configure Github Actions
The picture below is a screenshot of passing Actions. A badge is also attached below it
![screenshot1](https://github.com/Uchejen/Project2-azure-cloud-shell/blob/main/Screenshots/pythonapp.JPG?raw=true)
[![Python application test with Github Actions](https://github.com/Uchejen/Project2-azure-cloud-shell/actions/workflows/pythonapp.yml/badge.svg)](https://github.com/Uchejen/Project2-azure-cloud-shell/actions/workflows/pythonapp.yml)


