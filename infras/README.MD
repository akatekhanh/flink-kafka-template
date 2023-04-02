# How to run Flink infrastructure with Docker
**Version:**
- Flink 1.16.1
- Java 11

## Build the Flink docker image
```bash
docker build -t processor-flink-app .
```

## Start the image
```bash
docker run -it -p 8081:8081 -p 6123:6123 processor-flink-app bash 
```