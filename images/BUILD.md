```
docker buildx build --platform=linux/arm64,linux/amd64 --file images/Dockerfile.thick -t aluveitie/multus-cni:latest-thick -t aluveitie/multus-cni:4.0.2-thick --push .
```


docker buildx build --platform=linux/arm64,linux/amd64 --file Dockerfile -t aluveitie/bounca:latest -t aluveitie/bounca:0.4.4 --push .