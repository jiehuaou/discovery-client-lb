
##  spring cloud load-balancer work very well in spring boot 2.3.x with Spring cloud version Hoxton.SRX

pom.xml
``` 
<groupId>org.springframework.boot</groupId>
<artifactId>spring-boot-starter-parent</artifactId>
<version>2.3.3.RELEASE</version>
...
<java.version>1.8</java.version>
<spring-cloud.version>Hoxton.SR12</spring-cloud.version>
```

> spring cloud load-balancer can fetch healthy service instance list.


## spring cloud load-balancer does not work in spring boot 2.5.x with Spring cloud version 2020.0.X

pom.xml
``` 
<groupId>org.springframework.boot</groupId>
<artifactId>spring-boot-starter-parent</artifactId>
<version>2.5.4</version>
...
<java.version>1.8</java.version>
<spring-cloud.version>2020.0.3</spring-cloud.version>
```

> spring cloud load-balancer can not fetch service instance list or even fetch the unhealthy instance.

