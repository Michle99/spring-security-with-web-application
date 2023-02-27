### Securing a basic spring application with spring security

### Introduction
This is a basic maven spring application that shows how to apply spring security.
 
The concepts covered in this app are:
- Simple spring application
- Securing a spring application with spring security

### Pre-requisites
- Have a foundamental understanding of Java programming language.
- How to create a spring boot project.
- How to add dependencies such as spring security to the pom.xml.

###  Creating a Spring project
[Spring initializer is easy and fast way to get started creating a spring project] (https://start.spring.io)
You can add the spring security dependency by clicking the "add dependencies" button the top right side of the page and search for spring security. 

Alternatively, you can manually add the spring dependency in the pom.xml file by searching for spring security dependency in the [maven repository](https://mvnrepository.com), the spring dependency looks like so below:

```
<!-- https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-security -->
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-security</artifactId>
    <version>3.0.3</version>
</dependency>
```

### Getting Started
1. Download the code
2. Open the project in your favorite editor
3. Run the app
