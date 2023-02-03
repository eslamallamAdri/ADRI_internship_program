# Welcome to the ADRI internship program preliminary test

## Task 1:

#### 1.1 Create a public Github repository with the following name: **ADRI-Springboot-YOURNAME**

> (You will need to create a Github account if you don't already have one)

#### 1.2 Clone your repository on your local machine and intialize a SpringBoot folder with the following characteristics :

> (Hint: use [Spring Initializr](https://start.spring.io/))

- **Project Type:** Gradle
- **Language:** Java
- **SpringBoot version:** 2.7.8
- **Packaging:** Jar
- **Java Version:** 8
- **Group ID:** com.adri
- **Artifact ID / Name**: AdriInternship_**YOUR-NAME**

**Dependencies:**

- Spring Web
- Spring Data JPA

## Task 2:

#### 2.1 Download and Install [Docker-Desktop](https://www.docker.com/products/docker-desktop/).

#### 2.2 Use docker compose to create a mysql container with a user table.

1. Download the [docker_assets](./docker_assets/) folder into your local machine.
2. Open the folder in a terminal.
3. type the command `docker compose up -d` in your terminal to create your container.

## Task 3: Your first SpringBoot application

> Navigate back to your SpringBoot folder for this task

#### 2.1 Create an endpoint that returns a hello message to the user.

- **Method Type:** GET
- **Input:** None
- **Returns:** Hello message

#### 2.2 Create an endpoint that returns the specified user's information using their username.

- **Method Type:** GET
- **Request Param:** user_name (String)
- **Returns:** User information (JSON)

#### 2.3 Create an endpoint that adds a user to MySQL database.

- **Method Type:** POST
- **Input:** User Information (JSON)
- **Returns:** User Information (JSON)

## Resources:

- [Spring Boot Tutorial – Bootstrap a Simple Application](https://www.baeldung.com/spring-boot-start)
- [Spring Boot MySQL Integration: 6 Easy Steps](https://hevodata.com/learn/spring-boot-mysql/)
- [How to Use Docker Compose](https://www.linode.com/docs/guides/how-to-use-docker-compose/)



