## Automation testing stack using Java, Selenium, TestNG, and Maven.

The target website is [the internet.herokuapp](http://the-internet.herokuapp.com/). The "Parameters" annotation is used. 

Automated tests (for chrome and opera browsers):
1. Positive test sample for logging
2. Negative test sample for logging

## Executing the Tests

- Clone the repository:
```shell
git clone https://github.com/ViraHarasymiv/selenium_intro.git
```
- Run all tests:
```shell
mvn clean test
```
- run the logging positive test:
```shell
mvn -Dtest=PositiveLoginTest#logInTest test
```
- run the logging negative test:
```shell
mvn -Dtest=NegativeLoginTest#negativeTest test
```