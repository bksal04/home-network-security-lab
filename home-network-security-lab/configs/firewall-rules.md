# Firewall Rules and Segmentation Plan

## Segments
- Main network: trusted user devices
- IoT network: smart home or lower-trust devices
- Guest network: temporary devices with internet-only access

## Intended Policy
### Main Network
- Allow normal outbound internet access
- Allow management access to approved internal devices and services

### IoT Network
- Allow outbound internet access as required
- Block direct access to trusted user devices by default
- Permit only specific flows if needed for management

### Guest Network
- Allow DNS, HTTP, and HTTPS outbound traffic
- Deny access to all internal subnets

## Security Rationale
These rules reduce broadcast scope, improve control over traffic flows, and help prevent lateral movement from less trusted devices.
