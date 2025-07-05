# EM Config Server

**EM Config Server** is a centralized configuration service for the EM Microservices ecosystem. Built using **Spring Cloud Config Server**, it provides external configuration to distributed systems, supporting versioned and centralized management of properties across all environments.

---

## 📌 What is Spring Cloud Config?

Spring Cloud Config provides **server-side and client-side support** for externalized configuration in a distributed system. It allows microservices to fetch their configuration from a central place, typically a Git repository.

---

## 🚀 Key Features

- Centralized configuration management
- Git-based backend for version control
- Supports dynamic refresh of configuration (with Spring Cloud Bus)
- Environment-specific configuration (`dev`, `qa`, `prod`)
- Works with Spring Boot microservices using `bootstrap.yml`

---
