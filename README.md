<a name="readme-top"></a>
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#key-features">Key Features</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

# About The Project
A simple CRUD application by Spring Boot.

## Built With
* [![Java][Java-shield]][Java-url]
* [![Spring][Spring-shield]][Spring-url]
* [![Apache Maven][Apache Maven-shield]][Apache Maven-url]
* [![Apache Tomcat][Apache Tomcat-shield]][Apache Tomcat-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Getting Started

## Prerequisites
* [Java SE Development Kit 17](https://www.oracle.com/java/technologies/downloads/#java17): Of course you need to have Java installed to run a Java application. I used Java 17, but I think it works fine with other versions as well.
* [IntelliJ IDEA](https://www.jetbrains.com/idea/download/?section=windows): It is undoubtedly the top-choice IDE for software developers. It makes Java and Kotlin development a more productive and enjoyable experience.
* [H2 Database](https://www.h2database.com/html/main.html): an embedded, open-source, and in-memory database. It is a relational database management system written in Java. It is a client/server application. It is generally used in unit testing. It stores data in memory, not persist the data on disk.

## Installation
You can install this application by cloning this repository into your current working directory:
```sh
git clone https://github.com/theEmperorofDaiViet/crud-book.git
```
After cloning the repository, you can open the project by IntelliJ IDEA.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Key Features
- API: basic CRUD operations exposing Book resources with some simple validation:
  - findAll
  - findByTitle
  - findOne
  - create
  - delete
  - update
+ Persistence to an H2 in-memory database, using JPA.  
- Error handling: a simple centralized error handling mechanism using ***@ControllerAdvice***
+ Testing: JUnit tests that verifies the calls to the API, using REST Assured.
- Security: allow unrestricted access to all endpoints.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Contact

You can contact me via:
* [![GitHub][GitHub-shield]][GitHub-url]
* [![LinkedIn][LinkedIn-shield]][LinkedIn-url]
* ![Gmail][Gmail-shield]:&nbsp;<i>Khiet.To.05012001@gmail.com</i>
* [![Facebook][Facebook-shield]][Facebook-url]
* [![Twitter][Twitter-shield]][Twitter-url]

<br/>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- Tech stack -->
[Java-shield]: https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white
[Java-url]: https://www.java.com/
[Spring-shield]: https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white
[Spring-url]: https://spring.io/
[Apache Maven-shield]: https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white
[Apache Maven-url]: https://maven.apache.org/
[Apache Tomcat-shield]: https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black
[Apache Tomcat-url]: https://tomcat.apache.org/

<!-- Contact -->
[GitHub-shield]: https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white
[GitHub-url]: https://github.com/theEmperorofDaiViet
[LinkedIn-shield]: https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white
[LinkedIn-url]: https://www.linkedin.com/in/khiet-to/
[Gmail-shield]: https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white
[Facebook-shield]: https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white
[Facebook-url]: https://www.facebook.com/Khiet.To.Official/
[Twitter-shield]: https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white
[Twitter-url]: https://twitter.com/KhietTo