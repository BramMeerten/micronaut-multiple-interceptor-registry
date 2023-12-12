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
