# clamav
Scans the files from where the container is run for viruses using clamav.

## Build
```
docker build . -t clamav
```

## Run
```
docker run --rm -v $PWD:/scan -t clamav
```
