# clamav
Build all ``*.tex`` Files within the provided directory.

## Build
```
docker build . -t latex
```

## Run
```
docker run -i -v $PWD:/mount -t latex
```
