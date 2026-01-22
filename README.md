# Self-Hosted Media Server

## Overview
Personal Linux-based media server used to manage and stream media content.
The system runs containerized services using Docker and is maintained as an always-on home server.

This repository documents configuration decisions, service layout, and operational experience rather than application source code.

## Services
- Plex
- Jellyfin
- Sonarr
- Radarr
- Prowlarr
- qBittorrent (if applicable)

## Infrastructure
- Linux host
- Docker containers
- Persistent volumes for media and configuration
- Network port exposure and basic firewall configuration

## What I Did
- Deployed and configured media services as Docker containers
- Managed container volumes, networking, and restart policies
- Troubleshot DNS, networking, and service availability issues
- Performed routine updates and system maintenance to maintain uptime

## Repository Contents
- Documentation describing the system layout and services
- Example configuration files (with sensitive data removed)
- Notes on setup, maintenance, and known issues

## Status
Actively used personal system.
This repository exists to document infrastructure and operational decisions rather than provide a deployable product.
