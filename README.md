# AWS Application Load Balancer (ALB) vs Network Load Balancer (NLB) – Hands-on Project
## 🏗 Architecture Overview
![Architecture](https://github.com/vipul132/Network_and_Application_Load_Balancer-/blob/master/1.jpg))
## 📌 Project Overview
This project demonstrates a **hands-on implementation and comparison of AWS Application Load Balancer (ALB) and Network Load Balancer (NLB)**.  
The goal of this project is to understand the **exact differences, working layers, performance behavior, and real-world use cases** of both load balancers through practical testing.

Along with the implementation, a **short video walkthrough** has been created to explain the setup and observations.

---

## 🎯 Objectives
- Understand the difference between **Layer 7 and Layer 4 load balancing**
- Learn when to use **ALB vs NLB** in real-world AWS architectures
- Configure load balancers, listeners, and target groups
- Test traffic flow and health checks using EC2 instances

---

## 🏗️ Architecture Overview

### 🔹 Application Load Balancer (ALB)
- Works at **Layer 7 (HTTP/HTTPS)**
- Supports **path-based and host-based routing**
- Best for **web applications, REST APIs, and microservices**

### 🔹 Network Load Balancer (NLB)
- Works at **Layer 4 (TCP/UDP)**
- Provides **ultra-low latency and high throughput**
- Best for **real-time and high-performance workloads**

---

## 🛠️ Services Used
- Amazon EC2
- Application Load Balancer (ALB)
- Network Load Balancer (NLB)
- Target Groups
- Security Groups
- AWS VPC

---

## 🔧 Hands-on Tasks Performed
- Created EC2 instances for testing
- Configured **Application Load Balancer**
  - HTTP listener
  - Target group
  - Health checks
- Configured **Network Load Balancer**
  - TCP listener
  - Target group
- Attached EC2 instances to both load balancers
- Tested traffic routing and performance
- Observed differences in routing logic and latency

---

## 📊 Key Differences Observed

| Feature | ALB | NLB |
|------|----|----|
| OSI Layer | Layer 7 | Layer 4 |
| Protocols | HTTP / HTTPS | TCP / UDP |
| Routing | Path & host-based | Port-based |
| Latency | Moderate | Ultra-low |
| Use Case | Web apps, APIs | High-performance apps |

![Architecture](https://github.com/vipul132/Network_and_Application_Load_Balancer-/blob/master/2.jpg))
---

## 🎥 Video Walkthrough
A short video explaining the **complete setup and practical comparison** is available here:

👉 **YouTube Video:**  
*(Add your YouTube link here)*

---

## 📚 What I Learned
- Clear understanding of **ALB vs NLB use cases**
- Importance of choosing the right load balancer for application performance
- Practical experience with AWS load balancing concepts
- Hands-on exposure to real AWS production-style configurations

---

## 🚀 Future Enhancements
- Add HTTPS with ACM certificates
- Integrate Auto Scaling Groups
- Compare ALB + NLB with Gateway Load Balancer
- Performance testing using stress tools

---

## 👨‍💻 Author
**Vipul Pandey**  
Cloud & Systems Engineer  
🔗 LinkedIn: https://www.linkedin.com/in/vipul-pandey-1482b9162/

---

## ⭐ If you find this project useful
Give this repository a ⭐ and feel free to fork or contribute!
