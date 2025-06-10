# Ubuntu DevOps Toolkit 🐧🛠️

A lightweight toolkit of bash and Python scripts to simplify daily maintenance, debugging, and automation for Ubuntu servers.

## 🌟 Features

- Automated system updates and log rotation
- Disk health and space checks
- APT crash recovery script
- Simple process monitoring tools
- Utility for cleaning up old Docker images and stopped containers

## 📦 Scripts Included

| Script                    | Description                                 |
|---------------------------|---------------------------------------------|
| `update.sh`               | Auto-updates system packages and security   |
| `logrotate-enhanced.sh`   | Custom log rotation with gzip + timestamp   |
| `disk-check.py`           | Python script to check disk health          |
| `apt-fix.sh`              | Handles broken packages and apt locks       |
| `docker-clean.sh`         | Cleans unused Docker containers/images      |

## 🚀 Getting Started

```bash
git clone https://github.com/njerimargret/ubuntu-devops-toolkit.git
cd ubuntu-devops-toolkit
chmod +x *.sh
./update.sh
