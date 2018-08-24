# Basic CRUD App with Angular 7.0 and Spring Boot 2.1
 
This example app shows how to build a basic CRUD app with Spring Boot 2.1, Spring Data, and Angular 7.0.

**Prerequisites:** [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) and [Node.js](https://nodejs.org/). For Java 10+, you'll need to change the `java.version` property and `jaxb-api` as a dependency. See Josh Long's [spring-boot-and-java-10](https://github.com/joshlong/spring-boot-and-java-10) project on GitHub for more information.

* [Getting Started](#getting-started)
* [Links](#links)
* [Help](#help)
* [License](#license)

## Getting Started

To install this example application, run the following commands:

```bash
git clone https://github.com/riadh-mnasri/car-app.git
cd car-app
```

This will get a copy of the project installed locally. To install all of its dependencies and start each app, follow the instructions below.

To run the server, cd into the `server` folder and run:
 
```bash
./mvnw spring-boot:run
```

To run the client, cd into the `client` folder and run:
 
```bash
npm install && npm start
```

#### Tips and Tricks

Free used port :

```jshelllanguage
sudo kill $(sudo lsof -t -i:4200)
```

#### Reference

Please read [Build a Basic CRUD App with Angular 7.0 and Spring Boot 2.1](https://developer.okta.com/blog/2018/08/22/basic-crud-angular-7-and-spring-boot-2) to see how this app was created.

## License

Apache 2.0, see [LICENSE](LICENSE).
