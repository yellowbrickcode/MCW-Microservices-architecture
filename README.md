# Abstract

Contoso Events is an online service for concerts, sporting and other event ticket sales. They are redesigning their solution for scale with a microservices strategy and want to implement a POC for the path that receives the most traffic: ticket ordering.

## Workshop

In this workshop, you will look at the process of developing a proof of concept (POC) that will illustrate the use of many Azure features to support a highly scalable architecture based on Service Fabric, Functions and leveraging Azure Queues, CosmosDB, and other supporting features such as Azure AD and API Management. 

## Target Audience

There are two labs, one for each target audience:

* Application developer
* Infrastructure architect

## Whiteboard Design Session

This whiteboard design session is designed to help attendees gain a better understanding of implementing architectures leveraging aspects from microservices and serverless architectures, by helping an online concert ticket vendor survive the first 5 minutes of crushing load. They will handle the client's scaling needs through microservices built on top of Service Fabric, and apply smooth updates or roll back failing updates. Finally, students will design an implementation of load testing to optimize the architecture for handling spikes in traffic.

Attendees will learn how to:

-   Implement scale and resiliency with Service Fabric

-   Enable serverless solutions with Azure Functions

-   Control API access with API Management

-   Provide query flexibility with Cosmos DB

## Hands-on Lab

In this hands-on lab, you will construct an end-to-end POC for ticket ordering. You will leverage Service Fabric, API Management, Function Apps, Web Apps, and Cosmos DB.

![](HOL/images/Hands-onlabstep-by-step-Microservicesarchitecture-Infrastructureeditionimages/media/image2.png)


## Azure services and related products
- Azure Service Fabric
- Azure Resource Groups
- Azure API Management 
- Azure  API Apps
- Azure Active Directory
- Azure Web Apps
- Azure CosmosDB
- Azure Storage
- Azure Load Balancer
- Azure Queues
- Azure Functions


# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

