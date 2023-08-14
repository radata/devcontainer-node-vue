# Devcontianer vue

# Build Image
```bash
# build docker image
cd 16.20.1
docker build -t devcontainer-node-vue:1.20 .
```

## Networks
```bash
# create networks 
docker network create --subnet=172.17.11.0/24 --gateway=172.17.11.1 --opt "com.docker.network.bridge.name"="back" back
```
## Reopen in container

