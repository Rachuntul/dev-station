<a name="readme-top"></a>

<div align="center">
  <img src="https://img.shields.io/badge/Dev--Station-20232A?style=for-the-badge&logo=docker&logoColor=61DAFB" alt="Logo">
  <h3 align="center">RACHUN's Portable Dev-Station</h3>
  <p align="center">
    A lightweight, dockerized lab environment for a Daily Driver laptop.
    <br />
    <a href="https://github.com/Rachuntul/dev-station/issues">Report Bug</a>
    ·
    <a href="https://github.com/Rachuntul/dev-station/issues">Request Feature</a>
  </p>
</div>

---

## 📖 About
This repository is my personal command center. It manages essential services (DNS, Reverse Proxy, and Bots) using **Docker** to keep the host OS clean and stable.

### Built With
* [Docker & Compose](https://www.docker.com/)
* [Nginx Proxy Manager](https://nginxproxymanager.com/)
* [Debian Linux](https://www.debian.org/)

---

## 🚀 Getting Started

### Installation
1. Clone the repo with submodules:
```sh

	git clone --recursive [https://github.com/Rachuntul/dev-station.git](https://github.com/Rachuntul/dev-station.git)

```

2. Choose a service and deploy:
```sh

	cd core/nginx-proxy
	docker compose up -d

```



---

## 📂 Project Structure

* **`/core`**: Main infrastructure (Nginx Proxy Manager, AdGuard Home).
* **`/apps`**: Independent projects (linked via Git Submodules).

---

## ☕ Support

If this project helps you, feel free to support my research:
