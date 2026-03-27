# MY-DOCKER-APP

_Containerize and Deploy — A Python Web App Powered by Docker_

[![Last Commit](https://img.shields.io/badge/last%20commit-january%202026-black)]()  [![Dockerfile](https://img.shields.io/badge/dockerfile-66.4%25-blue)]()  [![Python](https://img.shields.io/badge/python-33.6%25-blue)]()  [![Languages](https://img.shields.io/badge/languages-2-blue)]()

Built with the tools and technologies:

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![DevContainers](https://img.shields.io/badge/Dev%20Containers-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

---

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)

---

## Overview

my-docker-app is a minimal Python web application fully containerized with Docker. It demonstrates how to package a Python app into a Docker image, run it in an isolated container, and configure a dev container environment for reproducible development.

### Why my-docker-app?

This project serves as a hands-on introduction to Docker-based development workflows. The core features include:

- 📦🐳 **Docker Containerization**: Package the Python app into a portable, reproducible Docker image.
- 🔧💻 **Dev Container Support**: Pre-configured `.devcontainer` for VS Code remote development.
- 🚀🔄 **Isolated Runtime**: Run the app in a clean, dependency-isolated container environment.
- 🐍🌐 **Python Web App**: Lightweight Flask/Python server running inside the container.

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Docker**: Install from [https://www.docker.com/](https://www.docker.com/)
- **Programming Language**: Python 3.8+

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/soumya0424/my-docker-app
   cd my-docker-app
   ```

### Usage

**Build and run with Docker:**

```bash
docker build -t my-docker-app .
docker run -p 5000:5000 my-docker-app
```

Then open `http://localhost:5000` in your browser.

**Or run locally:**

```bash
pip install -r requirements.txt
python app.py
```
