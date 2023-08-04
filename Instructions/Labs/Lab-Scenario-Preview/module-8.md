# Lab Scenario Preview: AZ-500: Implement Platform Protection

## Lab 08: Azure Firewall
You have been asked to install Azure Firewall. This will help your organization control inbound and outbound network access which is an important part of an overall network security plan. Specifically, you would like to create and test the following infrastructure components:
- A virtual network with a workload subnet and a jump host subnet.
- A virtual machine is each subnet. 
- A custom route that ensures all outbound workload traffic from the workload subnet must use the firewall.
- Firewall Application rules that only allow outbound traffic to www.bing.com. 
- Firewall Network rules that allow external DNS server lookups.

> For all the resources in this lab, we are using the **East US** region. Verify with your instructor this is the region to use for class. 

### Lab objectives

In this lab, you will complete the following exercise:

- Exercise 1: Deploy and test an Azure Firewall

### Architecture Diagram

![image](https://user-images.githubusercontent.com/91347931/157529954-a1bc434b-2eca-41c1-b875-1f0c977d5e20.png)
