# SoftUni Spring Data

Solutions for the SoftUni Spring Data course: JDBC, a hand-made ORM, Hibernate / JPA code first, Spring Data repositories
and queries, DTO mapping with ModelMapper, and JSON (Gson) / XML (JAXB) processing. Every lecture is its own Gradle
project.

## Lectures

| #   | Lecture | Exercises |
| --- | ------- | --------- |
| 001 | Database Access with JDBC | [Employees by Salary](001-Database-Access-With-Jdbc/src/main/java/Ex_1.java) · [Users' Games Count](001-Database-Access-With-Jdbc/src/main/java/Ex_2.java) |
| 002 | Exercise: Database Access with JDBC | Minions DB: [Get Villains' Names](002-Exercise-Database-Access-With-Jdbc/src/main/java/Ex_2.java) · [Get Minion Names](002-Exercise-Database-Access-With-Jdbc/src/main/java/Ex_3.java) · [Add Minion](002-Exercise-Database-Access-With-Jdbc/src/main/java/Ex_4.java) · [Change Town Names Casing](002-Exercise-Database-Access-With-Jdbc/src/main/java/Ex_5.java) · [Remove Villain](002-Exercise-Database-Access-With-Jdbc/src/main/java/Ex_6.java) · [Print All Minion Names](002-Exercise-Database-Access-With-Jdbc/src/main/java/Ex_7.java) · [Increase Minions Age](002-Exercise-Database-Access-With-Jdbc/src/main/java/Ex_8.java) · [Increase Age Stored Procedure](002-Exercise-Database-Access-With-Jdbc/src/main/java/Ex_9.java) |
| 003 | Workshop: Custom ORM | [Custom ORM](003-Workshop-Custom-ORM): `@Entity` / `@Id` / `@Column` annotations, reflection-based `EntityManager` over JDBC |
| 004 | Introduction to Hibernate | [Student](004-Introduction-To-Hibernate): first Hibernate entity and session |
| 005 | Exercise: Introduction to Hibernate | [SoftUni DB with JPA](005-Exercise-Introduction-To-Hibernate): employees, departments, projects, addresses, towns queries |
| 006 | Hibernate Code First | [Vehicles](006-Hibernate-Code-First): inheritance strategies, one-to-one / many-to-many mappings |
| 007 | Exercise: Hibernate Code First | [Code-first databases](007-Exercise-Hibernate-Code-First): wizard deposits, sales, university, hospital, bills payment |
| 008 | Spring Data Intro | [Accounts and users](008-Spring-Data-Intro): first Spring Data repositories and services |
| 009 | Exercise: Spring Data Intro | [Book Shop](009-Exercise-Spring-Data-Intro): authors, books, categories, seeding and queries |
| 010 | Spring Data Advanced Querying | [Shampoo Company](010-Spring-Data-Advanced-Querying): derived queries, `@Query`, JPQL |
| 011 | Exercise: Spring Data Advanced Querying | [Book Shop](011-Exercise-Spring-Data-Advanced-Querying): advanced queries, projections, updates and deletes |
| 012 | Spring Data Auto Mapping Objects | [Employees](012-Spring-Data-Auto-Mapping-Objects): DTOs with ModelMapper |
| 013 | Exercise: Spring Data Auto Mapping Objects | [Game Store](013-Exercise-Spring-Data-Auto-Mapping-Objects): users, games, orders, DTO mapping and validation |
| 014 | JSON Processing | [JSON demo](014-Json-Processing): Gson serialization |
| 015 | Exercise: JSON Processing | [Product Shop + Car Dealer](015-Exercise-Json-Processing): seed from JSON, export queries to JSON |
| 016 | XML Processing | [XML demo](016-Xml-Processing): JAXB, date adapters |
| 017 | Exercise: XML Processing | [Product Shop + Car Dealer](017-Exercise-Xml-Processing): seed from XML, export queries to XML |

## Run

Needs JDK 25, Gradle and MySQL on `localhost:3306` (the database lectures create or expect SoftUni's sample databases).

```bash
cd 011-Exercise-Spring-Data-Advanced-Querying
gradle build
gradle bootRun     # Spring Boot lectures
```

## Certificate

[SoftUni · Spring Data, June 2021](Resources/Certificate.pdf)

## License

[MIT](LICENSE)

## Course materials

Slides, task sheets and lecture videos for each lesson.

| Lesson | Materials | Video |
| ------ | --------- | ----- |
| [001-Database-Access-With-Jdbc](001-Database-Access-With-Jdbc) | [Diablo-Database.sql](001-Database-Access-With-Jdbc/Resources/Diablo-Database.sql) · [Soft-Uni-Database.sql](001-Database-Access-With-Jdbc/Resources/Soft-Uni-Database.sql) · [Spring-Data-Database-Access-With-Jdbc-Lab.pdf](001-Database-Access-With-Jdbc/Resources/Spring-Data-Database-Access-With-Jdbc-Lab.pdf) · [Spring-Data-Database-Access-With-Jdbc.pdf](001-Database-Access-With-Jdbc/Resources/Spring-Data-Database-Access-With-Jdbc.pdf) | [Video](https://youtu.be/gWIl72jnYIU) |
| [002-Exercise-Database-Access-With-Jdbc](002-Exercise-Database-Access-With-Jdbc) | [Minions-Db.sql](002-Exercise-Database-Access-With-Jdbc/Resources/Minions-Db.sql) · [Spring-Data-Database-Access-With-Jdbc-Exercises.pdf](002-Exercise-Database-Access-With-Jdbc/Resources/Spring-Data-Database-Access-With-Jdbc-Exercises.pdf) | [Video](https://youtu.be/wmVa2C6x6N4) |
| 003-Orm-Fundamentals | — | [Video](https://youtu.be/ip62X1wpLcE) |
| 004-Introduction-To-Hibernate | — | [Video](https://youtu.be/Kx-jfpnOHQQ) |
| 005-Exercise-Introduction to Hibernate | — | [Video](https://youtu.be/EIsxZ0QlyMU) |
| 006-Hibernate-Code-First | — | [Video](https://youtu.be/UILZKZYtrC0) |
| 007-Exercise-Hibernate-Code-First | — | [Video](https://youtu.be/QMZ3leweQJo) |
| [008-Spring-Data-Intro](008-Spring-Data-Intro) | [Spring-Data-Intro-Lab.pdf](008-Spring-Data-Intro/Resources/Spring-Data-Intro-Lab.pdf) · [Spring-Data-Intro.pdf](008-Spring-Data-Intro/Resources/Spring-Data-Intro.pdf) | [Video](https://youtu.be/hj7xVZODoqM) |
| 008-Intro-To-Spring-Framework | — | [Video](https://youtu.be/RweUDCFo5Ek) |
| [009-Exercise-Spring-Data-Intro](009-Exercise-Spring-Data-Intro) | [Spring-Data-Intro-Exercises.pdf](009-Exercise-Spring-Data-Intro/Resources/Spring-Data-Intro-Exercises.pdf) | [Video](https://youtu.be/5ya50xI_SQw) |
| [010-Spring-Data-Advanced-Querying](010-Spring-Data-Advanced-Querying) | [Spring-Data-Advanced-Querying-Exercises.pdf](010-Spring-Data-Advanced-Querying/Resources/Spring-Data-Advanced-Querying-Exercises.pdf) | [Video](https://youtu.be/R358HveKYZo) |
| [011-Exercise-Spring-Data-Advanced-Querying](011-Exercise-Spring-Data-Advanced-Querying) | [Spring-Data-Advanced-Querying-Exercises-.pdf](011-Exercise-Spring-Data-Advanced-Querying/Resources/Spring-Data-Advanced-Querying-Exercises-.pdf) | [Video](https://youtu.be/Bi58xpsLXTY) |
| [012-Spring-Data-Auto-Mapping-Objects](012-Spring-Data-Auto-Mapping-Objects) | [Spring-Data-Auto-Mapping-Objects-Lab.pdf](012-Spring-Data-Auto-Mapping-Objects/Resources/Spring-Data-Auto-Mapping-Objects-Lab.pdf) · [Spring-Data-Auto-Mapping-Objects.pdf](012-Spring-Data-Auto-Mapping-Objects/Resources/Spring-Data-Auto-Mapping-Objects.pdf) | [Video](https://youtu.be/zpLw-PJbSw8) |
| [013-Exercise-Spring-Data-Auto-Mapping-Objects](013-Exercise-Spring-Data-Auto-Mapping-Objects) | [Spring-Data-Auto-Mapping-Objects-Exercises.pdf](013-Exercise-Spring-Data-Auto-Mapping-Objects/Resources/Spring-Data-Auto-Mapping-Objects-Exercises.pdf) | [Video](https://youtu.be/NyyQuuT42aM) |
| [014-Json-Processing](014-Json-Processing) | [Json-Processing.pdf](014-Json-Processing/Resources/Json-Processing.pdf) | [Video](https://youtu.be/xYOOeSulp2E) |
| [015-Exercise-Json-Processing](015-Exercise-Json-Processing) | [Json-Processing-Exercises.pdf](015-Exercise-Json-Processing/Resources/Json-Processing-Exercises.pdf) | [Video](https://youtu.be/AMrdKmFyQf0) |
| [016-Xml-Processing](016-Xml-Processing) | [Xml-Processing.pdf](016-Xml-Processing/Resources/Xml-Processing.pdf) | [Video](https://youtu.be/FAZkUTJUUx0) |
| [017-Exercise-Xml-Processing](017-Exercise-Xml-Processing) | [Xml-Processing-Exercises.pdf](017-Exercise-Xml-Processing/Resources/Xml-Processing-Exercises.pdf) | [Video](https://youtu.be/zcZjMi3_NL4) |
