# Grafana monitoring

The aim is to run grafana in a container. This should monitor time series information.

## Building the containers

```bash
cd grafana
podman build -t grafana .
```

## Running the container
```bash
podman run -p 3000:3000 -d grafana .
```
