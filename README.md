# Arrow

Arrow is the codename for workshops led by Microsoft partners designed to help customers with the [Application build and deploy part of their DevOps strategy and practice](https://www.linkedin.com/pulse/how-leverage-partners-your-devops-strategy-practice-part-vito-chin). 

Arrow relates to the focused nature of these workshops, which is 1:1 between a partner and a customer. It also depicts the focused nature of the workshop content, which is customised based on a customer team's (customers are asked to involve a specific application team in the workshop) high level scenario.

This document goes through the high level agenda of the workshop as well as a few example customizations based on the high level agenda.

# High level agenda

* Build environment setup (teams, permissions), GitHub / Azure DevOps / self-hosted
* Connect build environment to Azure
* Source code hosting and considerations (monorepo, multi-repo)
* Example pipeline and workflow based on target Azure workload
* Retrospective and next steps 

# Examples

## Node.js, GitHub Free, Azure App Service

* The App is a Node.js web application and the customer is interested in deploying it to Azure App Service.
* The customer prefers to use GitHub Free after comparing it with Azure DevOps. They’re OK with the 2000 minutes hosted agent time for now.

Partner Customised Workshop Agenda:

*	Start with GitHub Free, discuss Organizations and teams (see The GitHub Guide to Organizations and Organizations and teams - GitHub Docs) (30 mins)
*	Connect GitHub environment to Azure (30 mins)
*	Discuss source code hosting structure (monorepo, multi-repo) (30 mins)
*	Demo Node.js to Azure App Service workflow (1 hour)
*	Retrospective and next steps (30 mins)

## Java Spring Boot, GitHub Enterprise, Spring Cloud, AKS

*	The App is a Spring Boot application, and the customer is interested in deploying it to Azure Spring Cloud or Azure Kubernetes Service.
*	The customer prefers to use GitHub Enterprise with Advanced Security after comparing it with Azure DevOps.
*	The customer is comparing between Azure Spring Cloud and Azure Kubernetes Service. They want to understand more about the CI/CD.

Partner Customised Workshop Agenda:

*	Start with GitHub Enterprise, discuss Organizations, Teams and Advanced Security (see The GitHub Guide to Organizations and Organizations and teams - GitHub Docs)(30mins)
*	Demo GitHub Advanced Security (15mins)
*	Connect GitHub environment to Azure (30 mins)
*	Discuss source code hosting structure (monorepo, multi-repo) (30 mins)
*	Demo Java to Azure Spring Cloud and Java to Azure Kubernetes Service (1 hour)
*	Retrospective and next steps (30 mins)
