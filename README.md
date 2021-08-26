# tdd

## The 'test' phase

- part of maven default lifecycle 
- all phases before test phase will pre-run 

```java
/data/workspaces/tdd$ mvn help:describe -Dcmd=test
```

and run test ...
```java
/data/workspaces/tdd$ mvn test
```
for more infos about mvn test parameters : [Maven - Running unit tests examples](https://www.logicbig.com/tutorials/build-tools/apache-maven/test-phase.html)


## Building and testing Java with Maven

*You can create a continuous integration (CI) workflow in GitHub Actions to build and test your Java project with Maven.*

[Github Actions : Build & test Java with Maven](https://docs.github.com/en/actions/guides/building-and-testing-java-with-maven)