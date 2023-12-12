Example for a problem I had with a Micronaut application:
https://github.com/micronaut-projects/micronaut-core/issues/10251

### Build Library
```
(cd lib;mvn clean install)
```

### Build app:
```
(cd app;mvn clean install;mvn jib:dockerBuild)
```

### Run app:
```
docker run module2
```
