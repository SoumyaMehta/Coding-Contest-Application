# Object Modeling

## Overview

Using object-oriented design to build a jukebox music application and a coding contest application. 

Development Involved:
*  Identifying and implementing the use cases, behaviors, and features of a Jukebox
*  Designing and implementing the application logic of running a coding contest
*  Implementing all the required layers step-by-step in a test-driven development style


# Pre-requisites

* Java 1.8/1.11/1.15
* Gradle 6

# Running the code

Use `run.sh` if you are on Linux/Unix/macOS Operating systems and `run.bat` if you are on Windows

Use the following scripts for their respective commands:
* `gradle clean build -x test --no-daemon` to create the jar file `geektrust.jar` in the `build/libs` folder.
* `java -jar build/libs/geektrust.jar sample_input/input1.txt` to execute the jar file passing in the sample input file as the command line argument.

Use the `build.gradle` file provided along with this project. 

Change the main class entry under the `jar` task in the `build.gradle` if your main class has changed:
```
 manifest {
        attributes 'Main-Class' : 'com.geektrust.backend.App' //Change this to the main class of your program which will be executed
    }
```

# Executing the unit tests

 `gradle clean test --no-daemon` will execute the unit tests.

# Help

You can read the build instructions [here](https://github.com/geektrust/coding-problem-artefacts/tree/master/Java) or reach me out at `isoumya.dev@gmail.com`

