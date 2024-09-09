# QA Playground Java

## Overview

`qa-playground-java` is a sandbox project designed to provide a comprehensive testing environment for both backend and frontend testing using Java. It includes essential libraries like Selenide for UI testing, Rest Assured for API testing, and TestNG for test management. The project is configured with logging support via SLF4J and Logback.

## Libraries 

- **Selenide**:
- **Rest Assured**
- **TestNG**
- **SLF4J API**
- **Logback Classic**

## Requirements

- **Java 17** or higher
- **Maven** 3.6 or higher

## Installation

1. Clone the repository:

    ```
   git clone git@github.com:jacekcho/qa-playground-java.git
   ```

2. Navigate to the project directory:

    ```
   cd qa-playground-java
   ```

3. Build the project using Maven or Maven wrapper:

    ```
   mvn clean install
   ```

   ```
   ./mvnw clean install
   ```

## Running Tests

### Frontend Tests

The project includes frontend tests using [Selenium](https://www.selenium.dev/documentation/webdriver/) or [Selenide](https://selenide.org/)

```
mvn test -Dtest=FrontendTest
```

### Backend Tests

For backend testing with [Rest Assured](https://rest-assured.io/), use the following command:

```
mvn test -Dtest=BackendTest
```
