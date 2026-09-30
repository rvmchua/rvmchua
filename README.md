<h1 align="center"> Hi there, I'm Royce 👋 </h1>
<div align="center">

  <h3>Backend Developer | Java & Spring Boot</h3>
  <p>📍 Caloocan, Metro Manila, Philippines</p>
  <a href="mailto:royce.chua@rvmchua.com"><img src="https://img.shields.io/badge/Email-royce.chua%40rvmchua.com-blue?style=for-the-badge&logo=gmail" alt="Email"></a>
</div>

---

## 👨‍💻 About Me

I am a Backend Developer specializing in **Java** and **Spring Boot**, with a deep interest in software architecture, networking, and systems administration. My path to software engineering is a bit unconventional: I graduated with a degree in Physics on a pre-med track from De La Salle University and spent three years in medical school before realizing that designing software and systems was what I truly wanted to pursue.

This rigorous scientific background shaped my analytical approach to problem-solving. Whether I'm designing an explicit state machine for an order lifecycle, implementing custom attribute-based access control, or configuring a homelab domain controller, I enjoy diving deep into how things work under the hood.

*   💻 **Current Focus:** Building robust REST APIs with Java and Spring Boot.
*   🐧 **Daily Driver:** Debian Trixie + i3 + zsh.
*   📝 **Knowledge Base:** Heavily reliant on Obsidian with Git-based sync.
*   📚 **Currently Learning:** Redis caching strategies and other data-intensive application.

---

## 🛠️ Tech Stack & Tools

**Backend**  
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)

**Infrastructure & Operations**  
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white)

---

## 🚀 Featured Projects

### 🍔 [Food Ordering REST API](https://github.com/rvmchua/ordertaker) *(In Development)*
*My primary backend portfolio project modeling a robust restaurant and order lifecycle.*
*   **Architecture:** Built in Spring Boot across four iterative phases (CRUD, Order Placement, State Machine, JWT Auth). 
*   **State Machine Design:** The order lifecycle (`Pending` -> `Confirmed` -> `Preparing` -> `For Pickup` -> `Received` / `Cancelled`) is modeled explicitly as a state machine. Status updates are handled via a single generic API endpoint validated against this machine on the server side.
*   **Data Modeling:** Kept the domain model clean by isolating Cart and CartItem tables from the order state machine. Implemented soft deletes with an approval step for restaurant profiles.
*   **Documentation:** Architecture and UML diagrams built with Mermaid, version-controlled alongside Obsidian notes.

### 🏥 Healthcare Portal & Immutable Audit Logger *(In Development)*
*A high-security backend for medical records focused on concurrency and strict access control.*
*   **Security & ABAC:** Implementing attribute-based access control (ABAC) using a custom Spring Expression Language (SpEL) security evaluator across 4 distinct user roles.
*   **Immutable Auditing:** Designing an append-only audit log using **Spring AOP** to ensure user actions are recorded seamlessly and cannot be altered.
*   **Concurrency Control:** Utilizing pessimistic locking to prevent race conditions (e.g., double-booking an appointment slot).
*   **Stack:** PostgreSQL (with Liquibase/Flyway), Spring Security (JWT), Redis, Docker Compose, Testcontainers, and Actuator/Micrometer for monitoring.

---

## 🖥️ Systems, IT & Homelab Experience

I believe good developers need to understand the infrastructure their code runs on. Beyond coding, I have hands-on experience deploying and troubleshooting real-world networks:

*   **Homelab Environment:** Built and maintain a Windows Server domain controller with Debian clients joined via Active Directory, Kerberos, and LDAP. I use Docker and VirtualBox for isolated, reproducible testing. 
*   **Systems Administration (2024 - 2025):** Act as the on-call IT/Network Administrator for my family's print business. I handle hardware troubleshooting, network deployment (APs and Ethernet drops), OS deployment, and endpoint security.
*   **Web & Email Security:** Deployed a personal site built with Hugo and hosted on Netlify, sitting behind Cloudflare. Configured strict email security policies (SPF, DKIM, and DMARC) to defend against spoofing and phishing.

---

## 📜 Certifications

*   **Java Programming (NCIII)** - *TESDA (Technical Education and Skills Development Authority)*
*   **Certified in Cybersecurity (CC)** - *ISC2 (Expired - Earned during my exploration of info-sec)*

---

## 📫 Let's Connect

I'm always open to discussing backend architecture, Java development, or trading homelab notes. 

*   **Email:** [royce.chua@rvmchua.com](mailto:royce.chua@rvmchua.com)
*   **Location:** Caloocan, Metro Manila, Philippines
