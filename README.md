## Build The Code

```
mvn clean install
```

## Deploy Swagger

```
cd pestore
mvn clean exec:java -Dexec.args="-c uat/api-config.json -h localhost -u admin -p admin -port 8075 -force -returnCodeMapping 10:0"
```