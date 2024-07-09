# Maven

- Maven projects contain a pom.xml file which is very important for running project

## pom.xml:

- Allows you to specify plugins, dependencies, properties/ version of dependencies needed to run your code.

Note: compile and test are usually the two tests you will be working with in maven/ pom.xml file.
Note: [search.maven.org](https://central.sonatype.com/?smo=true) has dependency structure avaiable on their website

To remove copies of classes created in target folder and removes target folder: mvn clean
to compile your maven project (creating class files): mvn compile
To test your unit tests within the maven project: mvn test
To compile, test and then place source code into a .jar file: mvn package
Checking if the maven project is a valid project: mvn validate

To clean, compile, test, package and then place everything into a maven repository: mvn install.

- A maven repository contains everything that maven has downloaded onto your local pc and can be accessed from a specific location.
