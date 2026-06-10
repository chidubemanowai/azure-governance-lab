# Azure Governance and Resource Deployment Summary

## Subscription and Resource Group

An Azure subscription was selected as the primary governance scope. A Resource Group named **rg-governance** was created to organize and manage resources deployed during this exercise.

## Selected Azure Region

**South Africa North (Johannesburg)** was selected because it is the closest Azure region to Nigeria and provides lower latency for workloads deployed from West Africa.

### Benefits

* Lower network latency
* Availability Zone support
* High availability and resilience
* Strong connectivity for African users

## Resource Deployment

A test Azure resource was deployed successfully to understand the deployment workflow, validation process, and resource management capabilities within Azure.

The deployment process included:

* Resource validation
* Subscription checks
* Region selection
* Resource Group assignment
* Deployment monitoring

## Shared Responsibility Model

The Shared Responsibility Model divides security and operational responsibilities between Microsoft and the customer.

### Microsoft Responsibilities

* Physical datacenter security
* Hardware maintenance
* Networking infrastructure
* Power and cooling
* Azure platform operations

### Customer Responsibilities

* Identity and access management
* Data protection
* Resource configuration
* Security settings
* Monitoring and compliance

For a Storage Account, Microsoft secures the infrastructure while the customer manages access permissions and protects the stored data.

## Cost Management

Azure Cost Management tools were explored to monitor usage and spending.

Features reviewed:

* Cost Analysis
* Budgets
* Cost Alerts
* Usage Monitoring

These tools help prevent unexpected charges and assist in staying within Free Tier limits.
