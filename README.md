# docker-tutorial-with-go

```bash
docker build -t hoge-image -f Dockerfile .
docker run -d --name fuga-container -p 3000:80 hoge-image:latest
```

### Multistage build
```bash
docker build -t hoge-image-multi -f Dockerfile.multistagebuild .
docker run -d --name fuga-container-multi -p 3001:80 hoge-image-multi:latest
```
