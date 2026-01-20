# 🖥️ Server Fundamentals – Interview Questions & Answers

A complete guide covering **server types, web servers, Linux, networking, security, deployment**, and **cloud basics**.  
Ideal for **backend / full-stack / DevOps interviews**.

---

## 📌 1. Server Basics

### Q1. What is a server?
**Answer:**  
A server is a system that listens for client requests, processes them, and sends responses over a network.

---

### Q2. What are the main types of servers?
**Answer:**  
- Physical Server  
- Virtual Server (VPS)  
- Shared Server  
- Dedicated Server  
- Cloud Server  

---

## 📌 2. Types of Servers (Detailed)

---

### Q3. What is a Physical Server?
**Answer:**  
A physical server is a standalone machine with its own CPU, RAM, and storage, dedicated to a single user or organization.

**Pros:** High performance, full control  
**Cons:** Expensive, hard to scale  

---

### Q4. What is a Virtual Server (VPS)?
**Answer:**  
A VPS is a virtual machine created from a physical server using virtualization, with allocated resources and its own OS.

**Pros:** Cost-effective, root access  
**Cons:** Limited resources  

---

### Q5. What is a Shared Server?
**Answer:**  
A shared server hosts multiple websites on the same server and OS, sharing all resources.

**Pros:** Very cheap, easy to use  
**Cons:** Low performance, limited control  

---

### Q6. What is a Dedicated Server?
**Answer:**  
A dedicated server is a full server rented by a single customer with complete access to hardware and software.

**Pros:** High performance, secure  
**Cons:** Expensive, needs admin skills  

---

### Q7. What is a Cloud Server?
**Answer:**  
A cloud server is a virtual server hosted in a cloud environment with on-demand scalability and pay-as-you-use pricing.

**Pros:** Highly scalable, reliable  
**Cons:** Ongoing cost  

---

## 📌 3. Web Servers

---

### Q8. What is Apache?
**Answer:**  
Apache is an open-source web server that handles HTTP/HTTPS requests and serves static or dynamic web content.

---

### Q9. What is the role of Apache?
**Answer:**  
- Handles client requests  
- Processes backend logic (PHP/modules)  
- Sends responses to users  

---

### Q10. What is Nginx?
**Answer:**  
Nginx is a high-performance, event-driven web server and reverse proxy designed for high concurrency.

---

### Q11. Nginx vs Apache?
**Answer:**

| Feature | Apache | Nginx |
|------|------|------|
| Architecture | Process-based | Event-driven |
| Performance | Moderate | Very High |
| RAM usage | High | Low |
| `.htaccess` | Yes | No |
| Best for | PHP apps | High-traffic apps |

---

## 📌 4. Linux Basics

---

### Q12. Why Linux is preferred for servers?
**Answer:**  
Linux is stable, secure, lightweight, open-source, and efficient for long-running services.

---

### Q13. Important Linux commands?
**Answer:**
```bash
ls, cd, pwd
cp, mv, rm
chmod, chown
ps, top
df -h, free -m
tail, grep
