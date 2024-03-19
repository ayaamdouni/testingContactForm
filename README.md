# Testing Contact Form

Welcome to the Testing Contact Form repository! This repository contains automated tests for an existing contact form in [this website]([https://chromedriver.chromium.org/downloads](https://www.webdriveruniversity.com/Contact-Us/contactus.html)), using Cucumber, Gherkin, Java, and Selenium. 

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Contributing](#contributing)

## Introduction

This repository hosts automated tests written in Java for testing a contact form. The tests are implemented using :
* Cucumber for behavior-driven development (BDD)
* Gherkin for writing human-readable scenarios
* Selenium for interacting with the web elements.

## Installation

To set up the testing environment locally, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/testing-contact-form.git
```
You can find the list of dependencies and their versions in the pom.xml file from this website : https://mvnrepository.com/

```code
    <dependencies>
        <!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java -->
        <dependency>
            <groupId>org.seleniumhq.selenium</groupId>
            <artifactId>selenium-java</artifactId>
            <version>4.16.1</version>
        </dependency>

        <!-- https://mvnrepository.com/artifact/io.cucumber/cucumber-java -->
        <dependency>
            <groupId>io.cucumber</groupId>
            <artifactId>cucumber-java</artifactId>
            <version>7.15.0</version>
        </dependency>

        <!-- https://mvnrepository.com/artifact/io.cucumber/cucumber-testng -->
        <dependency>
            <groupId>io.cucumber</groupId>
            <artifactId>cucumber-testng</artifactId>
            <version>7.15.0</version>
        </dependency>
    </dependencies>
```
Make sure to download the suitable chromeDriver based on your chrome version from [this website](https://chromedriver.chromium.org/downloads)
Replace the `chromedriver.exe` file located in the `drivers` directory of this repository with the downloaded ChromeDriver executable. This step ensures compatibility between the ChromeDriver version and your Chrome browser.

## Usage

To run the automated tests, follow these steps:

- Ensure the Selenium WebDriver is configured properly for your preferred browser.

- Open your IDE and navigate to the src/test/resources/features directory.

- Locate the `.feature` file containing the scenarios you want to execute.

Select the option to run 'Scenario:  Validate Successful Submission'.

Cucumber will execute the scenarios, and you'll see the test results in the console or the IDE's test runner interface.

![image](https://github.com/ayaamdouni/testingContactForm/assets/119370603/8ef7593b-5b0f-44f2-8df6-7cbec9fcab6a)

## Contributing

Contributions to this repository are highly encouraged! If you have any improvements, bug fixes, or new functions to add, feel free to fork this repository, make your changes, and submit a pull request.
