README
======

This README describes the spring-data-jpa-h2 project.

<br />

What is this?
---------------------------------------------------------
This repo is copied from this: https://github.com/sowdri/spring-data-mysql-java-config-sample/blob/master/READE.md

* A plain command line java program, simple!
* Java configuration, no XML
* Spring Data / JPA, and in memory H2 database


<br />

How to run?
---------------------------------------------------------
* ```mvn clean package```
* ```java -jar target/app.jar```


Note: if you need to adapt the code to your own path, make sure that you need to change the line in DataProvider.java, <br />
```lef.setPackagesToScan("com.learn.sdjpa.domain");```
