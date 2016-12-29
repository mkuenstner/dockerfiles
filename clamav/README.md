# clamav
Scans the files from where the container is run for viruses using [clamav](https://www.clamav.net/).

## Build
```
docker build . -t clamav
```

## Run
```
docker run --rm -v $PWD:/scan -t clamav
```
