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
```

# 🧠 Advanced Server & DevOps Interview Questions (Q&A)

These questions focus on **real-world scenarios**, **troubleshooting**, and **production-level knowledge**.

---

## 📌 1. Server Architecture & Performance

### Q1. What is server scalability?
**Answer:**  
Server scalability is the ability of a system to handle increased traffic by adding resources (vertical or horizontal scaling).

---

### Q2. Vertical vs Horizontal scaling?
**Answer:**  
- **Vertical Scaling:** Increase CPU/RAM of a server  
- **Horizontal Scaling:** Add more servers  

---

### Q3. What is high availability?
**Answer:**  
High availability ensures applications remain accessible even during failures.

---

### Q4. What is server redundancy?
**Answer:**  
Using multiple servers or components to avoid single points of failure.

---

## 📌 2. Nginx & Apache (Advanced)

---

### Q5. What is a virtual host?
**Answer:**  
A configuration that allows multiple websites to run on the same server using different domains.

---

### Q6. What is Nginx worker process?
**Answer:**  
A worker process handles client requests asynchronously using an event-driven model.

---

### Q7. What is keep-alive?
**Answer:**  
A feature that keeps the connection open to reuse it for multiple requests.

---

### Q8. Why is Nginx faster than Apache?
**Answer:**  
Because Nginx uses an event-driven architecture instead of a process-per-request model.

---

## 📌 3. Linux Administration

---

### Q9. What is a process in Linux?
**Answer:**  
A process is a running instance of a program.

---

### Q10. What is the difference between `ps` and `top`?
**Answer:**  
- `ps` shows a snapshot of processes  
- `top` shows real-time process usage  

---

### Q11. What is a daemon?
**Answer:**  
A background process that runs continuously (e.g. nginx, ssh).

---

### Q12. What is systemd?
**Answer:**  
Systemd is a service manager used to start, stop, and manage services.

---

## 📌 4. Networking & DNS

---

### Q13. What is DNS?
**Answer:**  
DNS converts domain names into IP addresses.

---

### Q14. What is TTL in DNS?
**Answer:**  
Time To Live defines how long DNS records are cached.

---

### Q15. What is a CDN?
**Answer:**  
A Content Delivery Network serves content from servers closest to the user.

---

### Q16. What is a socket?
**Answer:**  
A socket is an endpoint for network communication.

---

## 📌 5. Security (Very Important)

---

### Q17. What is DDoS attack?
**Answer:**  
A Distributed Denial-of-Service attack floods a server with traffic to make it unavailable.

---

### Q18. How does Nginx help against DDoS?
**Answer:**  
By rate limiting, connection limiting, and acting as a reverse proxy.

---

### Q19. What is HTTPS termination?
**Answer:**  
Decrypting SSL traffic at the reverse proxy level.

---

### Q20. What is CORS?
**Answer:**  
Cross-Origin Resource Sharing controls resource access between different origins.

---

## 📌 6. Node.js & Backend Servers

---

### Q21. Why is PM2 preferred over `node app.js`?
**Answer:**  
PM2 restarts apps on failure and supports clustering.

---

### Q22. What is clustering in Node.js?
**Answer:**  
Running multiple Node.js processes to utilize multi-core CPUs.

---

### Q23. What is environment-based configuration?
**Answer:**  
Different configs for development, staging, and production.

---

## 📌 7. Databases & Storage

---

### Q24. What is connection pooling?
**Answer:**  
Reusing database connections to improve performance.

---

### Q25. What is a backup strategy?
**Answer:**  
Regular, automated backups with secure storage and restore testing.

---

## 📌 8. Monitoring & Troubleshooting

---

### Q26. How do you check server memory usage?
**Answer:**
```bash
free -m
