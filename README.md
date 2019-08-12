# A React.js Application with Multi-Stage Docker Build
This application demonstrates how to:
* use `Dockerfile` for multi-stage build
* use `docker-compose` for multi-container applications.

## How to run for tests:
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
