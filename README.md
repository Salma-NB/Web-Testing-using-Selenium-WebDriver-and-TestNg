# Web-Testing-using-Selenium-WebDriver-and-TestNg
![GitHub last commit](https://img.shields.io/github/last-commit/Salma-NB/Web-Testing-using-Selenium-WebDriver-and-TestNg)
![GitHub](https://img.shields.io/github/license/Salma-NB/Web-Testing-using-Selenium-WebDriver-and-TestNg)

This repository contains a sample Selenium WebDriver project with TestNG and Java for automated web testing. It demonstrates best practices for writing Selenium test scripts and organizing your automation project.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Project Structure](#project-structure)
- [Reporting](#reporting)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

These instructions will help you set up and run the Selenium WebDriver project on your local machine.

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Java Development Kit (JDK) 8 or higher installed.
- Maven installed.
- Your favorite integrated development environment (IDE) set up for Java development (e.g., Eclipse, IntelliJ, or Visual Studio Code).
- Chrome or Firefox web browser installed (you can configure other browsers if needed).

### Installation

1. Clone this repository:
   git clone https://github.com/Salma-NB/Web-Testing-using-Selenium-WebDriver-and-TestNg.git

2. Navigate to the project directory:
cd Web-Testing-using-Selenium-WebDriver-and-TestNg

3. Install project dependencies using Maven:
mvn clean install


### Project Structure
The project follows a standard Maven project structure with the following important directories:

src/main/java: Java source code for your automation framework.
src/main/resources: Configuration files, property files, and any other resources.
src/test/java: TestNG test classes for your test scripts.
src/test/resources: TestNG XML files for test execution.
drivers: Store your WebDriver executable files (e.g., chromedriver, geckodriver) here.

### Reporting
TestNG generates test reports in the test-output directory. You can view them in your browser by opening the emailable-report.html or index.html file.

### Contributing
Feel free to contribute to this project by creating pull requests or opening issues. Please follow the project's coding standards and guidelines when submitting changes.

### License
This project is licensed under the MIT License.


