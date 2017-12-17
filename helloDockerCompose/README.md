### Running Manually

```bash
# Build Python Flask App
docker build -t helloFlask .

# Build Redis
docker run -d --name redis redis

# Linking Redis and Running helloFlask
docker run -P --link redis:redis helloFlask
```

### Running Using Docker Compose

```bash
docker-compose up
```
