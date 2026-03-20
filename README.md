# Tally-RDS-LAB
Centralized Tally ERP software deployment using Remote Desktop Services (RDS) to improve performance
## Objective
Improve the performance of Tally ERP by hosting it on a centralized Windows Server and allowing users to access it via Remote Desktop. Tally will auto-launch when users log in
## Statement of the Issue
Many organizations install Tally on client machines with limited resources, causing slow performance and productivity issues. Centralizing Tally on a powerful server solves this problem
## Proposed Solution
- Install Tally ERP software on a Windows Server  
- Deploy Remote Desktop Services (RDS) to allow multiple users to connect
- Create an OU,GROUP and an individual user accounts for each employee
- Configure Tally to auto-start when a user logs in via RDP using domain group policy  
