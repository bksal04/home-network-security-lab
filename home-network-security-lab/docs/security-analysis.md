# Security Analysis

## Threats Addressed
- Exposure of internal services through direct internet publishing
- Access to malicious or advertising domains through DNS
- Lateral movement between trusted and untrusted devices

## Controls Implemented
- DNS filtering with Pi-hole
- Encrypted remote access with Tailscale
- Documented segmentation and firewall strategy

## Residual Risks
- Devices on the same unrestricted segment may still trust each other too broadly
- Consumer networking hardware may limit VLAN or logging capability
- DNS filtering does not replace endpoint or perimeter protection

## Recommended Next Steps
- Enforce VLANs on managed switching hardware
- Centralise logs for better visibility
- Add vulnerability scanning and patch management routines
