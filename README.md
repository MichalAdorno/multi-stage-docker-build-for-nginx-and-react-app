[![Build Status](https://travis-ci.org/MichalAdorno/multi-stage-docker-build-for-nginx-and-react-app.svg?branch=master)](https://travis-ci.org/MichalAdorno/multi-stage-docker-build-for-nginx-and-react-app)
# A React.js Application with Multi-Stage Docker Build
This application demonstrates how to:
* use `Dockerfile` for multi-stage build
* use `docker-compose` for multi-container applications.

## How to run for tests:
```
docker build -t test -f Dockerfile.dev .
docker run -it test
```

## How to run for dev:
As above or:
```
docker-compose up --build
docker-compose down
```

## How to run for production:
```
docker build -t prod .
```

## How to open the application:
Open in a browser: `http://localhost:8080/`
