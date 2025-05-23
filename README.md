# Hello Java Maven – Jenkins Build Demo

This project is a basic Java "Hello World" application built using Maven and Jenkins as part of a DevOps internship task.

---

## Project Structure

hello-java-maven/
├── pom.xml
└── src/
└── main/
└── java/
└── HelloWorld.java


---

## What It Does

- Prints: `Hello, Jenkins + Maven!` to the console.
- Built using Maven.
- Automated using Jenkins Freestyle Job.

---

## Technologies Used

- Java (JDK 8 or 11)
- Apache Maven
- Jenkins (run via Docker)
- GitHub (for source code hosting)

---

## Jenkins Setup Summary

1.Jenkins Job Type: Freestyle project

2.Source Code: Pulled from GitHub repository

3.Build Step: Invoke top-level Maven targets

4.Goals: clean package

5.Result: Console shows BUILD SUCCESS

## How to Build with Maven

```bash

mvn clean package





