# Jakarta EE LS 

CANOSP Fall 2020 Project

- [jakartalsp](/jakarta.ls) - Jakarta EE LS
- [jakarta-eclipse](/jakarta-eclipse) - Eclipse Client that consumes the Jakarta EE LS

# Getting Started

1. Build the Jakarta EE LS: `mvn clean install` to create the `jarkata-ls-1.0-SNAPSHOT-jar-with-dependencies.jar` in the target directory

2. Import `jakarta-eclipse` and `jakartalsp` in Eclipse

3. Ensure that projects are being built with `JavaSE-1.8` ("Right-click project" --> "Properties" --> "Java Build Path" --> "Libraries")

4. Add the generated `jarkata-ls-1.0-SNAPSHOT-jar-with-dependencies.jar` to the `jakartaee-eclipse` folder

5. Ensure that jar is on the Java Build Path for the `jakarta-eclipse` project

5. Right-click on the project, "Run As" --> "Eclipse Application"

6. When you open up a Java file you should see the Jakarta EE server initializing and a sample diagnostic