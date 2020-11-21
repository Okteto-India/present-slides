# present-slides 


[![Develop on Okteto](https://okteto.com/develop-okteto.svg)](https://cloud.okteto.com/deploy?repository=https://github.com/Okteto-India/present-slides/)


# build Dockerfile
```
docker build -t gopherlabs .

```

# run container 
```
docker run -p 3999:3999 -t gopherlabs .

```

Reference :- https://pkg.go.dev/golang.org/x/tools/present


