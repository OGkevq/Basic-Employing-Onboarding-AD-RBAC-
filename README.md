# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* The fictional company Northstar Medical Group had been using a managed service provider(MSP) for its IT operations. Unfortunately, the MSP mishandled Northstar Medical Group's Identity Lifecycle Infrastructure. There was no organized process, and each user was added manually without the use of a Group Policy. This led to inconsistent permissions, employees being unable to do their jobs, and HIPAA Risks. Northstar decided it was best to separate itself from the MSP and start building its own environment.

## Solution Overview
* I built Northstar's identity infrastructure by creating the NMG.com Active Directory domain and promoting it to a Domain Controller. I then designed the Active Directory structure by creating Organizational Units (OUs) and security groups for the Finance, HR, IT, and Operations departments, implementing Role-Based Access Control (RBAC) to enforce consistent permissions and access management. Additionally, I resolved an urgent JIRA ticket (NGM-0047) by thoroughly investigating the issue, identifying the root cause, and documenting the resolution. The completed identity infrastructure followed the principle of least privilege, implemented RBAC, and supported HIPAA compliance.

## Video Walkthrough
Coming Soon

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
* Solved a mock ticket where a user had no access to her job software
* Documented solutions step by step
