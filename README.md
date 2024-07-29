[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/h7CYPb85)
# CMPG-323-Overview-37469878

## Introduction

This repository provides an overview of the CMPG 332 project. For each individual project, a separate repository will be created to store the code and documentation. The following section details the repositories that will be established for each project.

## Project 1: Analysis and Planning
**Repository Name**: CMPG 323 Overview 37469878  
**Description**: This repository holds the initial setup and configuration for the CMPG 323 projects. It includes milestones, labels, and a README file with comprehensive instructions.  
**Link**: [Project 1 Repository](#)  
**Milestone**: https://github.com/Samiie-ebb/CMPG-323-Overview-37469878/milestone/1

## Project 2: Web API
**Repository Name**: CMPG 323 37469878  
**Description**: This repository contains the implementation of a Web API using .NET C# MVC with JWT Security. It will also cover deployment to Azure.  
**Link**: [Project 2 Repository](#)  
**Milestone**: [Project 2 Submission](#) <!-- Replace # with the actual milestone link -->

## Project 3: Web Application
**Repository Name**: CMPG 323 WebApp 37469878  
**Description**: This repository focuses on developing a web application using .NET C# Blazor. It will follow the Repository Pattern and adhere to SOLID principles.  
**Link**: [Project 3 Repository](#)  
**Milestone**: [Project 3 Submission](#) <!-- Replace # with the actual milestone link -->

## Project 4: RPA Testing
**Repository Name**: CMPG 323 RPA Testing 37469878  
**Description**: This repository is dedicated to testing automation using RPA with UiPath.  
**Link**: [Project 4 Repository](#)  
**Milestone**: [Project 4 Submission](#) <!-- Replace # with the actual milestone link -->

## Project 5: Reporting and Data Visualization
**Repository Name**: CMPG 323 Reporting 37469878  
**Description**: This repository involves reporting, data visualization, and data analysis using Power BI and AI tools.  
**Link**: [Project 5 Repository](#)  
**Milestone**: [Project 5 Submission](#) <!-- Replace # with the actual milestone link -->
## Documentation
The detailed documentation for all projects can be found [here](#).

## Branching Strategy
We will use the Git Flow branching strategy in each project repository. This strategy includes the following branches:
- **main**: This branch contains the production-ready code.
- **develop**: This branch is used for development and integration of features.
- **feature/***: These branches are used for developing new features. Each feature branch is created from the develop branch.
- **release/***: These branches are used to prepare for a new release. Each release branch is created from the develop branch.
- **hotfix/***: These branches are used for quick fixes in the production code. Each hotfix branch is created from the main branch.

## .gitignore Usage
Each project repository will include a `.gitignore` file to exclude files and directories that should not be tracked by Git. This typically includes:
- Configuration files containing sensitive information
- Build and output directories
- Dependency directories (such as `node_modules` or `packages`)
- Temporary files and logs

## Storage of Credentials and Sensitive Information
Credentials and other sensitive information should never be stored directly in the repository. Instead, use environment variables or secret management tools provided by your hosting service (such as Azure Key Vault) to manage these securely. Additionally, ensure that the `.gitignore` file is configured to exclude any files that may contain sensitive information.

---
