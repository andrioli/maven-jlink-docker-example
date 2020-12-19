# maven-jlink-docker-example

[![Build Status](https://travis-ci.org/andrioli/maven-jlink-docker-example.svg?branch=master)](https://travis-ci.org/andrioli/maven-jlink-docker-example)

This project shows how you can build a tiny Docker image with a custom modular Java run-time image for your app.

## Prerequisites

- [JDK](http://jdk.java.net/)
- [Maven](https://maven.apache.org/)
- [Docker](https://www.docker.com/)

**You will need at least Java 9:** This project uses [jlink](https://docs.oracle.com/javase/9/tools/jlink.htm) to assemble modules and their dependencies into a custom Java run-time image.
