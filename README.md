# Hello Java Maven Project with Jenkins and Docker

This project demonstrates how to build and run a simple Java application using **Maven** with a **Jenkins CI/CD pipeline** inside Docker.

---

## 📌 Project Overview
- A simple Java program that prints:
     Hello Jenkins + Maven World
- Built using **Apache Maven**.
- Integrated with **Jenkins pipeline** for automated build and test.
- Packaged as a `.jar` file inside the Jenkins container.

---

## 🛠️ Tools & Technologies
- **Java** (OpenJDK 17)  
- **Maven** (Build tool)  
- **Jenkins** (CI/CD automation)  
- **Docker** (Containerization)  
- **GitHub** (Source code management)  

---

## 🚀 Steps Performed
1. Created a Maven project (`hello-java-maven`).
2. Wrote a simple `HelloWorld.java` program.
3. Configured `pom.xml` with `maven-jar-plugin` to set the main class.
4. Built the project using Maven in Jenkins:
 ```bash
 mvn clean install
5.Verified .jar in target/hello-1.0.0.jar.
6.Ran the program:
    java -cp target/hello-1.0.0.jar com.example.hello.HelloWorld
output:
      Hello Jenkins + Maven World

📂 Repository Structure

hello-java-maven/
│── src/
│   └── main/
│       └── java/com/example/hello/HelloWorld.java
│── screenshots/        # Jenkins build & execution screenshots
│── pom.xml
│── README.md

✨ Outcome
  Successfully integrated Java + Maven with Jenkins inside Docker.
  Automated build pipeline verified with proper output.
