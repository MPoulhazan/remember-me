# remember-me
All tips for FullStack Devs

## Maven

### Add prop file to config Intellij
```--spring.config.location=./src/test/resources/toto.yml --spring.config.name=toto.yml```

### Clean install skip SSL
```mvn clean install -U -Dmaven.wagon.http.ssl.insecure=true```

### Set Swagger active
```--spring.profiles.active=swagger```

