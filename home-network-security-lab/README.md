# Home Network Security Lab

## Overview
This project documents a home network security lab built around a Raspberry Pi 5, Pi-hole, and Tailscale. It is designed to demonstrate practical network administration, DNS filtering, secure remote access, and segmentation concepts that are directly relevant to entry-level networking and cybersecurity roles.

## Project Goals
- Improve home network visibility and control
- Filter malicious or unwanted DNS traffic
- Enable secure remote access without exposing services directly to the internet
- Document network segmentation and firewall policy design

## Current Environment
- Raspberry Pi 5 hosting Pi-hole and Tailscale
- Multiple home devices using Pi-hole for DNS resolution
- Tailscale mesh VPN providing encrypted remote connectivity
- Logical separation of trusted, IoT, and guest devices

## Technologies Used
- Raspberry Pi 5
- Pi-hole
- Tailscale
- Linux
- DNS filtering
- VLAN and firewall design concepts

## Key Features
- DNS-level filtering to block ads and potentially malicious domains
- Secure remote access through Tailscale without port forwarding
- Documented segmentation strategy for main, IoT, and guest devices
- Documented firewall rules to reduce lateral movement

## Repository Contents
- `configs/` contains setup and policy documentation
- `docs/` contains design and security analysis notes
- `images/` is for dashboard screenshots and your final network diagram

## Suggested Evidence to Add
- Pi-hole dashboard screenshot
- Tailscale devices screenshot
- Router or firewall screenshot
- Draw.io network diagram exported as PNG

## Outcome
This project demonstrates hands-on experience deploying and documenting network security tools in a real home environment.

## Future Improvements
- Add VLAN enforcement on managed switches or router
- Add IDS/IPS such as Suricata or Snort
- Add monitoring with Grafana, Prometheus, or syslog collection
