# Tailscale Docker

Run Tailscale (agent/relay) in a container

## How to use

### Docker

```bash
docker run -d \
  -e TAILSCALE_AUTH_KEY=<your_auth_key> \
  -v /dev/net/tun:/dev/net/tun \
  --network host \
  --privileged \
  moabukar/tailscale
```

### K8s setup


- TBC
