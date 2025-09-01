# Opinionated deployment automation of wg-easy

## Overview
This project automates the deployment of a self-hosted WireGuard VPN server using [wg-easy](https://github.com/WeeJeWel/wg-easy) and secures its web interface with [Traefik](https://traefik.io/) as a reverse proxy. The setup uses Ansible for provisioning and deployment, Docker Compose for service orchestration, and supports secure HTTPS access with automatic certificate management via Let's Encrypt.

## Features
- Automated provisioning of Ubuntu VM for secure access
- Dockerized deployment of WireGuard VPN (wg-easy)
- Traefik reverse proxy with HTTPS and basic authentication
- Ansible playbooks for idempotent setup and updates
- CI integration for hands-off deployment

## Prerequisites
- A VM running Ubuntu 22.04 or compatible Linux
- Root SSH access for initial provisioning
- Domain name pointing to your server

## Quick Start
// TODO: Add section

## CI Integration
// TODO: Add section

## Troubleshooting
- Ensure your firewall allows ports 80, 443 (TCP), and 51820 (UDP).
- DNS records for your domains must point to your server's public IP.
- For SSL errors, check Traefik logs and certificate configuration.

## License
MIT

## Credits
- [wg-easy](https://github.com/WeeJeWel/wg-easy)
- [Traefik](https://traefik.io/)
- [Ansible](https://www.ansible.com/)
