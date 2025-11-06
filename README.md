# Aplicacion de prueba

[![CI/CD Pipeline](https://github.com/diegobotia/labcicd/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/diegobotia/labcicd/actions/workflows/build.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=JhomarArrieta_AS-lab2-CI-CD&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=JhomarArrieta_AS-lab2-CI-CD)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=JhomarArrieta_AS-lab2-CI-CD&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=JhomarArrieta_AS-lab2-CI-CD)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=JhomarArrieta_AS-lab2-CI-CD&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=JhomarArrieta_AS-lab2-CI-CD)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=JhomarArrieta_AS-lab2-CI-CD&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=JhomarArrieta_AS-lab2-CI-CD)


Implementation of a Simple App with the next operations:

* Get random nations
* Get random currencies
* Get random airplanes
* Get application version
* health check

Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and Snyk

### Folders Structure

In the folder `src` is located the main code of the app

In the folder `test` is located the unit tests

### How to install it

Execute:

```shell
$ mvnw spring-boot:run
```
to download the node dependencies

### How to test it

Execute:

```shell
$ mvnw clean install
```

### How to get coverage test

Execute:

```shell
$ mvwn -B package -DskipTests --file pom.xml
```