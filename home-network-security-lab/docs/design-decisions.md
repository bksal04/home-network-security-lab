# Design Decisions

## Why Pi-hole
Pi-hole was chosen because it provides centralised DNS filtering, simple deployment on Raspberry Pi hardware, and clear visibility into DNS activity across multiple devices.

## Why Tailscale
Tailscale was chosen because it provides modern encrypted remote connectivity with minimal configuration and avoids exposing management services through public-facing port forwarding.

## Why Segmentation
Segmenting trusted, IoT, and guest devices helps reduce risk if a lower-trust device is compromised. It also reflects common enterprise security principles applied at home-lab scale.
