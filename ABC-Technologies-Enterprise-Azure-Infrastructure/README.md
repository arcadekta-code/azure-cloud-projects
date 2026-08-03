# ABC Technologies - Enterprise Azure Infrastructure Deployment

## Project Overview

This project demonstrates the deployment of a complete Azure infrastructure for ABC Technologies.

The infrastructure was built on Microsoft Azure by creating networking resources, deploying a Windows Server Virtual Machine, configuring IIS Web Server, hosting a training website, and validating secure access through Azure networking components.

This project was completed as part of my Azure Administrator (AZ-104) hands-on learning journey.

---

## Business Scenario

ABC Technologies wanted to host an internal training website on Microsoft Azure.

The solution required:

- Organizing resources using a Resource Group
- Creating secure Azure networking
- Deploying a Windows Server Virtual Machine
- Installing IIS Web Server
- Hosting a training website
- Testing website accessibility
- Managing Azure resources
- Optimizing Azure costs after deployment

---

# Azure Services Used

- Azure Resource Groups
- Azure Virtual Network (VNet)
- Azure Subnet
- Network Security Group (NSG)
- Public IP Address
- Windows Server Virtual Machine
- IIS (Internet Information Services)
- Azure Virtual Network Interface (NIC)
- Azure Storage (Managed OS Disk)
- Azure Monitoring


---

# Architecture

The infrastructure was deployed using the following Azure architecture.

> **Architecture diagram will be added here after project completion.**


---

# Deployment Workflow

The following deployment sequence was followed during the project implementation.

1. Create Resource Group
2. Create Virtual Network
3. Create Subnet
4. Create Network Security Group (NSG)
5. Create Public IP Address
6. Deploy Windows Server Virtual Machine
7. Connect to VM using Remote Desktop (RDP)
8. Install IIS Web Server
9. Deploy Sample Website
10. Test Website using Public IP
11. Stop and Deallocate Virtual Machine
12. Clean up Azure Resources


---

# Skills Demonstrated

## Azure Administration

- Resource Group Management
- Azure Virtual Network (VNet)
- Subnet Configuration
- Network Security Group (NSG)
- Public IP Management
- Windows Server Virtual Machine Deployment
- Azure Resource Management
- Azure Cost Optimization

## Windows Administration

- Remote Desktop (RDP)
- IIS Web Server Installation
- Website Hosting
- Basic Windows Server Administration

## Cloud Concepts

- Infrastructure as a Service (IaaS)
- Azure Resource Organization
- Virtual Networking
- Secure Resource Deployment
- Cloud Cost Management

---

# Azure Resource Naming Convention

| Azure Resource | Name |
|----------------|------------------------------------------------|
| Resource Group | rg-abctech-prod-malaysiawest-01 |
| Virtual Machine | vm-abctech-prod-web-01 |
| Virtual Network | vnet-abctech-prod-malaysiawest-01 |
| Subnet | snet-web |
| Region | Malaysia West |
| Subscription | Azure for Students |

Following a consistent naming convention improves resource management, troubleshooting, automation, and governance.
