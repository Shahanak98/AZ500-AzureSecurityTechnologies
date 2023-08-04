# Lab Scenario Preview: AZ-500: Manage Identity and Access - Part B

## Lab 05: Azure AD Privileged Identity Management
You have been asked to create a proof of concept that uses Azure Privileged Identity Management (PIM) to enable just-in-time administration and control the number of users who can perform privileged operations. The specific requirements are:
- Create a permanent assignment of the aaduser2 Azure AD user to the Security Administrator role. 
- Configure the aaduser2 Azure AD user to be eligible for the Billing Administrator and Global Reader roles.
- Configure the Global Reader role activation to require an approval of the aaduser3 Azure AD user
- Configure an access review of the Global Reader role and review auditing capabilities.

> For all the resources in this lab, we are using the **East US** region. Verify with your instructor this is the region to use for class. 

> Before you proceed, ensure that you have completed Lab 04: MFA, Conditional Access and AAD Identity Protection . You will need the Azure AD tenant, AdatumLab500-04, and the aaduser1, aaduser2, and aaduser3 user accounts.

### Lab objectives
In this lab, you will complete the following exercises:
- Exercise 1: Configure PIM users and roles.
- Exercise 2: Activate PIM roles with and without approval.
- Exercise 3: Create an Access Review and review PIM auditing features.

### Architecture Diagram

![image](https://user-images.githubusercontent.com/91347931/157522920-264ce57e-5c55-4a9d-8f35-e046e1a1e219.png)
