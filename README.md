# Tailscale Docker

Run Tailscale (agent/relay) in a container

## How to use

### Docker

```bash
docker run -d \
  -e TAILSCALE_AUTH_KEY=<your_auth_key> \
  --privileged \
  moabukar/tailscale

## Check it's running

`docker logs <container_id>` and you should see that the container is connected to the network.

```

### K8s setup


- TBC
