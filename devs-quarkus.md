Run Quarkus Native:
```shell
oc new-app quay.io/quarkus/ubi-quarkus-native-s2i:22.2-java11~https://github.com/quarkusio/quarkus-quickstarts.git \
    --context-dir=getting-started \
    --name=quarkus-quickstart-native
```
