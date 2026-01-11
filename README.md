# Photon-HFT

![Java](https://img.shields.io/badge/Java-21-orange?style=for-the-badge&logo=java&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Event--Driven-blue?style=for-the-badge)
![Latency](https://img.shields.io/badge/Latency-Ultra--Low-red?style=for-the-badge)

**Photon-HFT** is an ultra-low latency, distributed High-Frequency Trading (HFT) platform engineered in **Java 21**. It features a sharded, zero-garbage architecture that achieves **10 Million RPS** on a Ryzen 7950X3D.

Built with **Mechanical Sympathy** in mind, the system bypasses standard abstractions to utilize **Aeron** (IPC/UDP), **SBE** (Binary Serialization), and **Agrona** (Lock-free Data Structures), ensuring deterministic microsecond-level performance. The platform includes a full DevSecOps pipeline, ensuring production-grade reliability from day one.

## 🛠️ Tech Stack

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Language** | ![Java](https://img.shields.io/badge/Java-21-orange?style=flat-square&logo=java&logoColor=white) | Core runtime (Temurin JDK) with ZGC & Vector API support. |
| **Transport** | ![Aeron](https://img.shields.io/badge/Aeron-1.44-purple?style=flat-square) | Low-latency IPC & UDP Multicast transport. |
| **Serialization** | ![SBE](https://img.shields.io/badge/SBE-1.30-blue?style=flat-square) | Zero-copy binary protocol (Fintech standard). |
| **Data Structures** | ![Agrona](https://img.shields.io/badge/Agrona-1.20-blue?style=flat-square) | Lock-free queues, off-heap maps & buffers. |
| **Web Gateway** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.4-green?style=flat-square&logo=springboot&logoColor=white) | Reactive WebSockets (Netty) & REST API. |
| **Frontend** | ![SolidJS](https://img.shields.io/badge/SolidJS-1.8-333333?style=flat-square&logo=solid&logoColor=white) | High-performance reactive UI for real-time charts. |
| **Containerization** | ![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=flat-square&logo=docker&logoColor=white) | Host-mode networking for bare-metal speed. |
| **Build Tool** | ![Maven](https://img.shields.io/badge/Maven-3.9-C71A36?style=flat-square&logo=apachemaven&logoColor=white) | Multi-module build & dependency management. |
| **Security** | ![SonarQube](https://img.shields.io/badge/SonarQube-DevSecOps-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white) | Automated vulnerability scanning & quality gates. |


