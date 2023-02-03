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

> This will create a Msql database called **adri** with username: **intern** and password: **intern123**

## Task 3: Your first SpringBoot application

> Navigate back to your SpringBoot folder for this task

#### 3.1 Create an endpoint that returns a hello message to the user.

- **Method Type:** GET
- **Input:** None
- **Returns:** Hello message

#### 3.2 Create an endpoint that returns the specified user's information using their username.

- **Method Type:** GET
- **Request Param:** user_name (String)
- **Returns:** User information (JSON)

#### 3.3 Create an endpoint that adds a user to MySQL database.

- **Method Type:** POST
- **Input:** User Information (JSON)
- **Returns:** User Information (JSON)

## Task 4: Theory Questions

Add a **README.md** file like this one [Example_README.md](Example_README.md) to your repository and put your answers in it.
> Please answer these questions in your own way

#### Q1. In your own words, what is an API?

#### Q2. What's the difference between SQL and NoSQL databases?

#### Q3. What is Git and what is it used for?

#### Q4. What constitutes clean code?

## Submission:

Submit a link to your Github repository to this [Google form](https://forms.gle/WVPcZrL6syk3ty7V7)

## Resources:

- [Spring Boot Tutorial – Bootstrap a Simple Application](https://www.baeldung.com/spring-boot-start)
- [Spring Boot MySQL Integration: 6 Easy Steps](https://hevodata.com/learn/spring-boot-mysql/)
- [How to Use Docker Compose](https://www.linode.com/docs/guides/how-to-use-docker-compose/)



