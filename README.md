# Aiven Kafka HTTP Connector

[![Build Status](https://travis-ci.org/aiven/aiven-kafka-connect-http.svg?branch=master)](https://travis-ci.org/aiven/aiven-kafka-connect-http)

![HTTP logo](doc/IETF-Badge-HTTP.png)

This is a sink [Kafka Connect](https://kafka.apache.org/documentation/#connect) connector that sends Kafka records over HTTP.

TBD

## Development

The connector supports Java 11 or later. It uses [Gradle](https://gradle.org/) for building and automating tasks.

To build a distribution:
```bash
./gradlew clean check distTar distZip
```
(check `build/distributions/` then).

Integration tests can be run with 
```bash
./gradlew integrationTest
```
and require [Docker](https://www.docker.com/) installed.

## License

This project is licensed under the [Apache License, Version 2.0](LICENSE).
