# Selenium Automation Script for Table Search Demo

This automation script validates the search functionality of the **Selenium Playground Table Search Demo** using **Java**, **Selenium WebDriver**, and **Cucumber** (BDD framework).

## Setup and Installation

### 1. Prerequisites

- Java 11 or higher
- Maven
- Your preferred IDE (Eclipse, IntelliJ, etc.)
  
### 2. Install Required Dependencies

If using Maven, add the following dependencies in your `pom.xml` file.

### 3. Set Up WebDriver

This script uses **WebDriverManager** to automatically download and manage the required browser driver (ChromeDriver). Ensure you have an active internet connection during execution.

### 4. Feature File

The **feature file** (`SearchFunctionality.feature`) defines the test scenario. It follows **Gherkin syntax** for BDD.

### 5. Running the Test

Run the test by executing the **TestRunner** class, which uses **JUnit** and **Cucumber**.

To run the test:

1. Run the `TestRunner` class in your IDE.
2. View the results in the **HTML report** generated under the `target/cucumber-reports` folder.

### 6. Test Details

- **Feature**: The script navigates to the Selenium Playground Table Search Demo page, enters "New York" in the search box, and verifies that 5 search results appear out of a total of 24 entries.

---

## Best Practices Followed

- **BDD (Behavior Driven Development)** approach with **Cucumber** to improve collaboration.
- **Assertions** are used for result validation to ensure test reliability.
- WebDriverManager is used to handle browser driver versions automatically.

### Dependencies

- **Selenium**: Used to automate browser interactions.
- **Cucumber**: Framework for BDD and feature-based test case writing.
- **JUnit**: For running the tests.
