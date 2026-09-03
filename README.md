# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
The problem we are having in a company called Northstar Medical Group is that was not properly organized, The Users were provisioned manaually with no naming convintion, the Users where also assigned to different access, there is malfunctioning of Organation Unit (OU) Structure, an inconsistent group membership, which lead more than 300 employees in the company into HIPAA compliance explosure. 
## Solution Overview
I was able to provide the solution for this company in less than a week. I build a NMG.com domain in a windows server, designed a department based OU structure with four business Units. Implimenting RBAC using security groups mopped to each department, and provisioned 15 user accounts with consistent SAMAccountName and UPN formating accross four department. I diagnozed and resolved a multi-cause identity incident involving in current OU placement and missing security group membership. 

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* [Add your second key accomplishment here]
* [Add your third key accomplishment here]
