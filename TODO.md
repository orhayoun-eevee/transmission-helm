# Transmission Chart Operational Notes

## Connectivity & Networking

- Peer-to-peer egress policy must be validated in each target cluster before production rollout.
- If outbound peer discovery is restricted, route Transmission through an approved egress gateway/proxy and document the selected path in environment-specific values.
