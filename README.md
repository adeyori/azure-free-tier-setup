# Azure Free Tier Account Setup

## Project Overview

This project documents the setup of my Microsoft Azure Free Tier account. The aim was to create an active Azure environment, explore the Azure Portal, understand subscriptions and resource groups, deploy a basic cloud resource, and review cost management tools.

## Azure Account and Subscription

I created a Microsoft Azure account and accessed the Azure Portal successfully. I confirmed that my Azure subscription was active and available for use.

Evidence: `screenshots/Azure-1.jpeg`

## Resource Group Created

I created a resource group to organize the resources for this mini project.

- Resource Group Name: `rg-yori-test-lab-02`
- Region: `West Europe`
- Purpose: To serve as a logical container for the test Azure resources used in this project.

Evidence: `screenshots/Azure-2.jpeg`

## Region Selection

I selected `West Europe` as the region for my resources. This region was chosen because it is one of the closest Azure regions to Nigeria and is suitable for reducing latency compared with regions farther away.

## Resource Deployed

For the test deployment, I created a basic Azure Storage Account.

- Resource Type: Storage Account
- Resource Group: `rg-yori-test-lab-02`
- Region: `West Europe`
- Redundancy: Locally-redundant storage (LRS)

This helped me understand the Azure resource creation process, including configuration, validation, and deployment.

Evidence: `screenshots/03-Azure-3.jpeg`

## Identity and Access Awareness

I explored Microsoft Entra ID, formerly known as Azure Active Directory. This helped me understand that Azure uses identity management to control users, permissions, and access to cloud resources. I also reviewed the idea of Role-Based Access Control (RBAC), which allows users to be given only the level of access they need.

## Shared Responsibility Model

The Shared Responsibility Model explains the division of security duties between Microsoft and the customer.

For the Storage Account I deployed, Microsoft is responsible for protecting the physical data centers, networking infrastructure, and the underlying cloud platform. I am responsible for how I configure the storage account, who I allow to access it, how I manage permissions, and how I protect my account credentials.

This means Microsoft secures the cloud infrastructure, while I am responsible for securing what I create inside the cloud.

## Cost Management

I accessed the Cost Management section of Azure to review cost analysis and budget options. This is important because cloud resources can generate charges if they are not monitored properly.

Evidence: `screenshots/04-Azure-4.jpeg`

## Conclusion

This mini project helped me understand the basic process of setting up an Azure Free Tier account, navigating the Azure Portal, creating a resource group, deploying a simple resource, and checking cost management tools. It also introduced me to important cloud concepts such as subscriptions, regions, RBAC, and the Shared Responsibility Model.
