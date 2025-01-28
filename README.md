### 4.2_Spring_Framework_Basics_Level1
## CRUD exercise with H2

Access the page ->https://start.spring.io/, and generate a Spring boot project with the following characteristics:

#### PROJECT (dependency manager)

* Maven or Gradle

#### LANGUAGE

* Java

#### SPRING BOOT

* Latest stable version

#### PROJECT METADATA

* Group: cat.itacademy.s04.t02.n01

* Artifact: S04T02N01

* Name: S04T02N01

* Description: S04T02N01GognomsNom

* Package name: cat.itacademy.s04.t02.n01

#### PACKAGING

* Jar

#### JAVA

* Minimum version 11

#### Dependencies

* Spring Boot DevTools

* Spring Web

* Spring Data JPA

* H2 Database

We have an entity called "Fruit", which has the following properties:

* int id
* String name
* int weightInKilograms

Using the JPA specification, you will have to persist this entity to an H2 database, following the MVC pattern. For this, depending on the main Package, you will create a package structure, where you will place the classes you need:

 * cat.itacademy.s04.t02.n01.controllers
 * cat.itacademy.s04.t02.n01.model
 * cat.itacademy.s04.t02.n01.services
 * cat.itacademy.s04.t02.n01.repository
 *cat.itacademy.s04.t02.n01.exception

The class located in the controllers package (FruitaController, for example), must be able to respond to the following requests to update and consult information:

* http://localhost:8080/fruit/add
* http://localhost:8080/fruit/update
* http://localhost:8080/fruit/delete/{id}
* http://localhost:8080/fruit/getOne/{id}
* http://localhost:8080/fruit/getAll
