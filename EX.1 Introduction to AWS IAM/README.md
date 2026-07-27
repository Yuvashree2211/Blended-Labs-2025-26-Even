# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**  
<img width="1906" height="967" alt="image" src="https://github.com/user-attachments/assets/5a385832-bb64-4530-bd21-3da2b7c1ca67" />


<img width="1917" height="1017" alt="image" src="https://github.com/user-attachments/assets/86fcfd02-07ea-4914-96d9-58ff1ebfdc97" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**
<img width="1917" height="1020" alt="image" src="https://github.com/user-attachments/assets/8c695e1f-b0d1-426c-862e-fdaeb333791a" />



<img width="1917" height="1015" alt="image" src="https://github.com/user-attachments/assets/4a152ffa-e93e-4525-9909-af821f8a670b" />

  
<img width="1903" height="1015" alt="image" src="https://github.com/user-attachments/assets/e0a86e0c-9bc3-409b-bd3e-b9599853b2b0" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  

<img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/d5515c5d-c4cc-4bf7-b14b-dbb1460ecb45" />


<img width="1917" height="1078" alt="Screenshot 2026-07-27 141308" src="https://github.com/user-attachments/assets/2c243d09-8dc2-495e-82e7-d97ec8458543" />


qw<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/40d7103c-a3d5-4b82-8d57-4e2a1a22b014" />


## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** YUVASHREE R (212224040378)
**Course:** Introduction to Cloud Computing  

