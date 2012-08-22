# Open Charge Point Protocol v1.1

You can find more details on the [official website](http://www.ocpp.nl/)

## Incudes

* CentralSystemService-1.1.wsdl generated scala beans
* ChargePointService-1.1.wsdl generated scala beans
* Helper methods to work with ocpp



## Setup

1. Add this repository to your pom.xml:
```xml
    <repository>
        <id>thenewmotion</id>
        <name>The New Motion Repository</name>
        <url>http://nexus.thenewmotion.com/content/repositories/releases-public</url>
    </repository>
```

2. Add dependency to your pom.xml:
```xml
    <dependency>
        <groupId>com.thenewmotion.chargenetwork</groupId>
        <artifactId>ocpp</artifactId>
        <version>2.6</version>
    </dependency>
```