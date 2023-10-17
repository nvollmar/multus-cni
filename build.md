docker buildx build --platform=linux/arm64,linux/amd64 --file images/Dockerfile.thick -t aluveitie/multus-cni:latest-thick -t aluveitie/multus-cni:4.0.2-thick --push .
