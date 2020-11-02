# Build a docker image

```bash
docker build -t ckad-java-sample .
```

# Tagging 

```bash
docker tag <image id> saihitesh1998/ckad-java-sample
```

# Testing locally before push to hub

```bash
docker run saihitesh1998/ckad-java-sample
```

# Pushing to dockerhub

```bash
docker push saihitesh1998/ckad-java-sample
```
