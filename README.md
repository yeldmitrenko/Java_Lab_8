# Java_Lab_8
### Task
 - Write code for Lab 2
 - Use java code convention
 - CLasses must be distributed in packages
 - Work with console must be minimal
 - Code must contain only that classes that are described in the diagram
 - Sorting must use java built-in methods
 - Sorting must be implemented in separate method
 - No static methods/attributes are allowed (the only exception is a main method)
 - You must use an Enum
 - Code must be in a separate branch with PR
 - Comparison must be implemented using lambdas
 - Instead of getters/setters you should use @Data annotation from lombok
 - Use maven and Jococo(in build section), FindBugs, PMD, CheckStyle plugins(reporting section)
 - Run `mvn site` and fix errors reported by checkstyle, pmd and findbugs

## To run:
 - git clone 
 - Intellij IDEA: push 'RUN'
## Or:
 - `cd` into repo folder
 - Run `mvn compile`
 - Run `mvn exec:java -Dexec.mainClass=ua.lviv.iot.equipment.App` 
