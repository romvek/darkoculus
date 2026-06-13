# Darkoculus

A passive eye over the threat landscape. Self-hosted RSS aggregator for cybersecurity OSINT.

## Stack
- Ubuntu 26.04 LTS
- PHP 8.5.4 + extensions
- Nginx 
- SQLite3 
## Architecture
## Phase 1 — LXC Foundation
### Environment
- OS: Ubuntu 26.04 LTS
- Static IP: `X.X.X.X`
- Disk: 8GB | RAM: 512MB | CPU: 1 core
- Hostname: darkoculus
### User & Basic Hardening 
- OS Updates
- Create a non-root user
- Set up SSH key auth if not done already
- Disable root SSH login
- Set up UFW for ssh and http

## Phase 2 — FreshRSS Install
### Stack
- PHP 8.5 + extensions
- Nginx
- SQLite3
- FreshRSS

## Phase 3 — Feed Import & Categories
## Phase 4 — Homarr Integration
## Notes & Lessons Learned
