## build image

```
docker build -t gcr.io/broyal-demo-354814/file-server .
```

## run local test

```
docker run -d -p 80:80 gcr.io/broyal-demo-354814/file-server
```