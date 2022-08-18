Run Quarkus Native:
```shell
oc new-app quay.io/quarkus/ubi-quarkus-native-s2i:22.2-java11~https://github.com/quarkusio/quarkus-quickstarts.git \
    --context-dir=getting-started \
    --name=quarkus-quickstart-native
```

OpenJDK Environment Variables:
```properties
AB_JOLOKIA_OFF=true
JAVA_INITIAL_MEM_RATIO=50
JAVA_MAX_MEM_RATIO=100
GC_MAX_METASPACE_SIZE=200
```
