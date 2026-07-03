# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* The problem in this project was related to a fictional company called Northstar Medical Group. Northstar Medical Group used a third-party MSP that mismanaged their Identity Lifestyle workflow. As the company scaled, the lack of RBAC policies created gaps that risked HIPAA violations. Northstar Medical Group needed a professional to create a new system from scratch to eliminate the issues and solve the problem in order to mitigate any future security risks. 

## Solution Overview
* The solution was to build a basic employee onboarding pipeline in Active Directory. I created the domain server, named it NMG.com, and built Organizational Units (OUs) and Security Groups so that users were only granted access to tools relative to their role — enforcing the principle of least privilege. To test the system, I created a simulated mock ticket where a user was provisioned the incorrect level of access. I resolved it by reading the ticket, investigating the issue, forming a hypothesis, verifying that hypothesis before applying any fixes, making the correct changes, and confirming the fix resolved all symptoms of the problem. This closed the compliance gap the MSP had left open and enforced least-privilege access across the domain.

## Video Walkthrough
https://www.loom.com/share/470d5798bfb645ceab66494db77bc4e8
https://www.youtube.com/watch?v=3jOiM-MHWB8

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
