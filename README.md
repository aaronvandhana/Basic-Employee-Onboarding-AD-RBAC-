# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* The problem in this project was related to a fictional company called Northstar Medical Group. Northstar Medical Group used a third-party MSP that mismanaged their Identity Lifestyle workflow. As the company scaled, the lack of RBAC policies created gaps that risked HIPAA violations. Northstar Medical Group needed a professional to create a new system from scratch to eliminate the issues and solve the problem in order mitigate any future security risks. 

## Solution Overview
* The solution was to build a basic employee onboarding pipeline in Active Directory.  I created the Domain Server and named it NMG.com and created Organizational Units (OU) and Security Groups to make sure when users are onboarded, they were only given access to tools ONLY relative to their role. Eliminated the compliance gap by enforcing least-privilege access via RBAC. A simulated mock ticket was also created where a user was provisioned the incorrect level of access. The ticket was solved by reading the ticket, investigating the issue, creating a hypothesis, verified the hypothesis before applying fixes, make the correct changes, and finally verified the fix and solved all symptoms of the problem. 

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
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
* Familiarized myself with RBAC and its importance with security risks
* Solved a technical issue beyond the scope of the contents of the ticket description by investigating the problem in full and resolving the root of the issue.
