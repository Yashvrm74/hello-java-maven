# Hello Java Maven - Jenkins CI Build

This repository contains a simple Java application built using Maven.  
It is used to demonstrate a basic CI pipeline setup with Jenkins.

## Contents

- `HelloWorld.java`: A basic Java program that prints a message.
- `pom.xml`: Maven configuration file to build the project.

## How to Build

Run the following Maven command:

```bash
mvn clean package
```

## Jenkins Setup

A Jenkins Freestyle job was created to build this project using the `clean package` goal.  
The job pulls the code from this GitHub repository and executes the Maven build.
