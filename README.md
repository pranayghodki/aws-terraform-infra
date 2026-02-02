\# AWS Infrastructure Automation using Terraform



This project demonstrates \*\*Infrastructure as Code (IaC)\*\* by provisioning AWS infrastructure using \*\*Terraform\*\*.  

All resources are created and destroyed using Terraform commands in a reproducible and automated way.



---



\## 🚀 Project Overview



This project automates the creation of AWS infrastructure, including:



\- Virtual Private Cloud (VPC)

\- Public Subnet

\- Security Group (SSH \& HTTP access)

\- EC2 Instance (Free Tier compatible)



The objective is to manage cloud infrastructure using \*\*code instead of manual configuration\*\*.



---



\## 🛠️ Technologies Used



\- Terraform

\- AWS (EC2, VPC, Security Groups)

\- AWS CLI

\- Git \& GitHub

\- Linux Basics



---



\## 📁 Project Structure



aws-terraform-project

│── provider.tf

│── variables.tf

│── vpc.tf

│── ec2.tf

│── .gitignore

│── README.md





---



\## ⚙️ Prerequisites



Before running this project, ensure you have:



\- An AWS account

\- IAM user with programmatic access

\- Terraform installed

\- AWS CLI configured



---



\## 🔐 AWS Configuration



Configure AWS credentials using:



```bash

aws configure

Enter the following details:



AWS Access Key ID



AWS Secret Access Key



Default region (e.g. ap-south-1)



Output format: json



▶️ How to Run the Project

1️⃣ Initialize Terraform

terraform init

2️⃣ Review Execution Plan

terraform plan

3️⃣ Apply Configuration

terraform apply

Type yes when prompted.



🧨 Destroy Infrastructure (Important)

To avoid AWS charges, destroy all resources after testing:



terraform destroy

Type yes to confirm.



🧠 Key Learnings

Implemented Infrastructure as Code using Terraform



Automated AWS resource provisioning



Managed cloud infrastructure lifecycle



Handled AWS Free Tier limitations



Followed best practices for state and credential management



📌 Best Practices Followed

Excluded sensitive files using .gitignore



Did not commit Terraform state files



No AWS credentials stored in the repository



Clean and modular Terraform configuration



✍️ Author

Pranay Ghodki

DevOps Enthusiast | CI/CD | Docker | Terraform



📄 Note

This project is created for learning and demonstration purposes.





---



\## ✅ Ab kya karna hai (quick reminder)

```bat

notepad README.md

