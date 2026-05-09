<a name="readme-top"></a>

<br />
<div align="center">
  <a href="https://github.com/Rachuntul/dev-station">
    <img src="https://img.shields.io/badge/Dev--Station-20232A?style=for-the-badge&logo=docker&logoColor=61DAFB" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Personal Portable Dev-Station</h3>

  <p align="center">
    A lightweight, dockerized lab environment optimized for a Daily Driver laptop.
    <br />
    <a href="https://github.com/Rachuntul/dev-station"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Rachuntul/dev-station/issues">Report Bug</a>
    ·
    <a href="https://github.com/Rachuntul/dev-station/issues">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#project-structure">Project Structure</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project

This repository serves as my personal command center. Since I use my laptop as a **Daily Driver**, I need a way to run various services (DNS, Reverse Proxy, Bots) without cluttering my Debian host OS. Every service here is containerized for maximum portability and performance.

### Built With
* [Docker](https://www.docker.com/)
* [Nginx Proxy Manager](https://nginxproxymanager.com/)
* [Debian Linux](https://www.debian.org/)
* [Python](https://www.python.org/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites
* Docker & Docker Compose installed.
* Basic understanding of Networking/Ports.

### Installation
1. Clone the repo
   ```sh
   git clone --recursive [https://github.com/Rachuntul/dev-station.git](https://github.com/Rachuntul/dev-station.git)

```

2. Navigate to a service folder
```sh
cd core/nginx-proxy

```


3. Spin up the container
```sh
docker compose up -d

```



## Project Structure

* **`/core`**: Main infrastructure (NPM, AdGuard Home).
* **`/apps`**: Independent projects (linked via Git Submodules).
* **`/monitoring`**: System health and performance tracking.

## Contact

Dion Puji Ramdani - [@Rachuntul](https://github.com/Rachuntul)

Project Link: [https://github.com/Rachuntul/dev-station](https://github.com/Rachuntul/dev-station)

## Support My Lab

```

---

