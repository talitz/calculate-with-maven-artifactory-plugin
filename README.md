# Calculate - Experiments with Maven Artifactory Plugin
A tiny repo for running small experiments in CI/CD

- Contains a tiny maven project
- Contains a single class with 4 methods
- Contains simple unit tests

The code and the tests can be easily tweaked to introduce various error conditons for testing the CI/CD pipeline

<b>Deploy to Artifactory using the following command:</b></br>

```cd maths && mvn clean deploy -Dusername=admin -Dpassword=<YOUR-PASSWORD> -Dbuildnumber=7 -s settings.xml```
