# azurewebappv1

### Run tests
`$ ./mvnw clean verify`

### Run locally
```shell
$ docker-compose -f docker/docker-compose.yml up -d
$ ./mvnw spring-boot:run -Dspring-boot.run.profiles=local
### Login with device code
$ .az login --use-device-code
### Maven plugin to deploy application
$ ./mvn azure-webapp:deploy
### config information
mvn azure-webapp:config
### 
# Pom.xml file has a entry to do the azure-webapp. Config information adds the entry for the config information

#run the command prompt  

```


### Useful Links
* Swagger UI: http://localhost:8080/swagger-ui.html
* Actuator Endpoint: http://localhost:8080/actuator
