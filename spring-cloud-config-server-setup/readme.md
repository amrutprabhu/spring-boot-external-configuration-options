# Spring Cloud Config Example
<a href="https://foojay.io/works-with-openjdk"><img align="right" src="https://github.com/foojayio/badges/raw/main/works_with_openjdk/Works-with-OpenJDK.png" width="100"></a>

In this example we are exploring how we can integrate spring cloud config with a client so that we can fetch configuration stored in a git repo and is served by the spring cloud config server. 

Here we also see how we can modify the configuration and define separate repos for the configuration. 

This is all based on the new spring cloud 2020.0 release version, which have some breaking changes compared to previous version. 

The project is based on JDK 17. 

To start the server just run the following command. 

```shell
java -jar target/config-server-0.0.1-SNAPSHOT.jar  
```

You can then start the client with the following command.

```shell
java -jar target/config-client-service-0.0.1-SNAPSHOT.jar \
--spring.profiles.active=prod

```

You can read about this on my website [https://refactorfirst.com](https://refactorfirst.com)


