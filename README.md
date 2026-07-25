# HomeLab

## Overview

This project documents the design and implementation of my personal HomeLab used to develop practical experience with networking, Linux administration, virtualization, Docker containers, home automation, and security.

The goal is to simulate technologies commonly found in enterprise environments while providing useful services within my home.

---

## Objectives

- Learn more Linux administration
- Build a Docker environment
- Deploy Home Assistant
- Implement UniFi networking
- Deploy Frigate NVR
- Manage container networking
- Learn reverse proxy concepts
- Practice backup and disaster recovery
- Gain hands-on networking experience

---

## Hardware

| Device | Purpose |
|---------|----------|
| Mini PC | Docker Host |
| UniFi Gateway | Routing & Firewall |
| UniFi PoE Switch | Camera and AP Power |
| UniFi Access Point | Wireless Network |
| PoE Camera | Frigate Detection |

---

## Software Stack

- Ubuntu Server
- Docker
- Docker Compose
- Home Assistant
- Frigate
- MQTT
- UniFi Network
- Git
- VS Code

---

## Current Architecture

Internet
↓

ISP Modem
↓

UniFi Gateway
↓

PoE Switch
├── Mini PC
├── Camera
└── Access Point

Mini PC
├── Docker
│   ├── Home Assistant
│   ├── Frigate
│   ├── MQTT
│   └── Future Containers

---

## Current Services

| Service | Status |
|-----------|---------|
| Docker | ✅ |
| Home Assistant | ✅ |
| Frigate | ✅ |
| MQTT | Planned |
| Pi-hole | Planned |
| WireGuard VPN | Planned |
| Grafana | Planned |
| Prometheus | Planned |

---

## Skills Demonstrated

- Linux CLI
- Docker Networking
- Container Management
- Network Design
- VLAN Planning
- Firewall Concepts
- Git Version Control
- YAML Configuration
- Troubleshooting
- IP Addressing
- DNS
- Home Automation

---

## Lessons Learned

Some notable lessons from this project include:

- Docker bind mounts
- Volume persistence
- Container networking
- Port conflicts
- RTSP camera configuration
- MQTT integration
- YAML syntax troubleshooting
- VLAN segmentation

---

## Future Improvements

- Reverse Proxy
- HTTPS certificates
- Grafana dashboards
- Prometheus monitoring
- NAS integration
- Automated backups
- Kubernetes experimentation

---

## Project Status

🚧 Active Development
