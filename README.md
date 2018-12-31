# build-images
Custom Docker images for building.

### Dockerfile.OpenJDK8

- Adds imulab.io.crt to CA certificate chain, so this image can use all home lab services.

```
docker build -t davidiamyou/open-jdk-8:latest . -f Dockerfile.OpenJDK8
docker push davidiamyou/open-jdk-8:latest
```