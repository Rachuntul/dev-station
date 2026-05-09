# 🚀 My Personal Portable Dev-Station

<p align="center">
  <img src="https://img.shields.io/badge/Status-Maintained-success?style=flat-square" alt="Maintained">
  <img src="https://img.shields.io/badge/OS-Debian%2012-blue?style=flat-square&logo=debian" alt="OS Debian">
  <img src="https://img.shields.io/badge/Infrastructure-Docker-blue?style=flat-square&logo=docker" alt="Docker">
  <img src="https://img.shields.io/badge/License-MIT-orange?style=flat-square" alt="License MIT">
</p>

### 💻 Overview
A lightweight, dockerized lab environment optimized for a **Daily Driver** laptop. This setup manages local development services, network-wide privacy, and automation bots without cluttering the host OS.

---

## 🛠 Core Services
| Service | Purpose | Stack |
| :--- | :--- | :--- |
| **Nginx Proxy Manager** | Handles `.local` domains & SSL | Nginx, MariaDB |
| **AdGuard Home** | Network-wide DNS & Ad-blocking | Go |
| **Photo Converter Bot** | Automated Telegram image utility | Python/Docker |
| **Warp Tunnel** | Privacy-focused outbound gateway | Cloudflare |

## 📂 Project Architecture
```text
dev-station/
├── core/       # Critical infrastructure (NPM, AdGuard)
├── apps/       # Custom bots and dev projects
└── monitoring/ # System health tracking (Uptime Kuma)

## 🚀 Quick Start

Every service is containerized. To deploy a specific module:
Bash

cd core/nginx-proxy
docker compose up -d

## ☕ Support the Research

If you find my projects useful or want to support my cybersecurity & development journey, feel free to buy me a coffee!
