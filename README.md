# Tiny Java WebApp (Servlet + Maven)

A minimal Java 17 web application using Servlet API 5.0 and built with Maven. Deployable on Tomcat 10+.

---

## Features

- Java 17 compatible
- Jakarta Servlet API 5.0
- WAR packaging
- Simple "Hello, World!" endpoint at `/hello`

---
---

## Requirements

- Java 17+
- Maven 3.6+
- Apache Tomcat 10.0+ (Jakarta EE 9 compatible)

---
## Project Structure

- tiny-webapp/
- ├── pom.xml
- └── src/
- └── main/
- ├── java/
- │ └── com/example/HelloServlet.java
- └── webapp/
- ├── index.html
- └── WEB-INF/web.xml

---
## Build Instructions

1. Clone the repo or create the folder structure manually.
2. Navigate to the project root:

```bash
cd tiny-webapp

Build the WAR file:
mvn clean package

Deploy the generated target/tiny-webapp.war to your Tomcat webapps/ directory.

Running the App
Start Tomcat.

Open your browser and visit:
http://localhost:8080/tiny-webapp/hello

You should see:
Hello, World!

Notes:
This project uses Jakarta Servlet API, not the older javax.servlet package.
Make sure to use Tomcat 10 or newer, older versions (like Tomcat 9) will not work.



