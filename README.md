# Monoplane Server Distribution

This an example runtime assembly, that demonstrates how the different components can be integrated in Wildfly.

## Build the server

```
mvn antrun:run -Pdev install
```

### Run the server

```
cd target/wildfly-8.2.0.Final
./binstandalone.sh -c standalone-mono.xml  -Dcassandra.boot_without_jna=true

```



