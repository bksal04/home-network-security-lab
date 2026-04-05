# Tailscale Setup

## Purpose
Tailscale was deployed to provide encrypted remote access to the home lab without exposing services through public port forwarding.

## Configuration Summary
- Installed Tailscale on the Raspberry Pi 5
- Enrolled the Pi and client devices into the same tailnet
- Verified remote connectivity between approved devices
- Used Tailscale as a secure administrative path into the lab environment

## Security Value
Using a mesh VPN reduces the attack surface compared with directly exposing SSH, web dashboards, or other management interfaces to the public internet.

## Validation
- Confirmed device visibility in the Tailscale admin view
- Tested encrypted remote access from multiple devices
- Verified services remained reachable without port forwarding
