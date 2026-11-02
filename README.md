# demo

A simple deployment demo app for students (mongodb)

**Stack** : Java 17, Maven, Spring Boot 3.0.5, MongoDB

## Démarrage

```bash
./mvnw clean install   # construire et tester
./mvnw spring-boot:run   # démarrer l'application
./mvnw test   # lancer les tests
```

## Docker

```bash
docker compose -f docker-compose.yaml up --build
```

## Structure

```
src/
docker-compose.yaml
mvnw
mvnw.cmd
pom.xml
```
