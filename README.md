# 🌐 Build a Virtual Private Cloud (VPC) on AWS

## 📌 Project Overview

In this project, I created a custom Virtual Private Cloud (VPC) in AWS to understand cloud networking fundamentals such as subnets, routing, and internet connectivity.

This project demonstrates how to design a secure and scalable network for deploying cloud resources like EC2 instances.

---

## 🚀 What I Built

* Custom VPC with CIDR block
* Public Subnet
* Internet Gateway (IGW)
* Route Table configuration
* Enabled public internet access for instances

---

## 🧠 Key Concepts Learned

* What a VPC is and why it's used
* Difference between public and private subnets
* Importance of route tables
* How Internet Gateway enables internet access
* IP addressing using CIDR blocks

---

## 🛠️ Steps I Followed

### 1. Created a VPC

* Defined IPv4 CIDR block (e.g., 10.0.0.0/16)

### 2. Created a Subnet

* Created subnet in Mumbai region
* Enabled auto-assign public IPv4

### 3. Created and Attached Internet Gateway

* Created IGW
* Attached it to my VPC

### 4. Configured Route Table

* Added route:

  * Destination: 0.0.0.0/0
  * Target: Internet Gateway

### 5. Associated Subnet with Route Table

* Linked subnet to route table to make it public

---

## ⚠️ Challenges Faced

One important thing I learned:

> Just naming a subnet "public" does NOT make it public.

It only becomes public when:

* It has a route to an Internet Gateway

---

## ⏱️ Time Taken

* Approximately 1–2 hours
* Most time spent understanding how components work together

---

## 📷 Architecture Diagram (Optional)
<img width="1873" height="659" alt="Screenshot 2025-07-02 162919" src="https://github.com/user-attachments/assets/b031eb0c-2337-432f-9ac6-79b5ec452385" />

<img width="1574" height="298" alt="Screenshot 2025-07-02 170604" src="https://github.com/user-attachments/assets/065b2096-ac02-4a21-ba81-7359df309f7c" />

<img width="1005" height="246" alt="Screenshot 2025-07-02 174838" src="https://github.com/user-attachments/assets/330d4f02-64c2-4ef6-8e1e-909ab24c90ae" />



---

## 📚 Tools & Services Used

* AWS VPC
* AWS Management Console

---

## 🎯 Outcome

Successfully built a working VPC with internet access, gaining hands-on experience in AWS networking.

---

## 🔗 Future Improvements

* Add private subnet
* Deploy EC2 instance inside VPC
* Configure NAT Gateway
* Implement security groups and NACLs

---

## 🙌 Author

**Abhijeet Pandit**

