# Jukebox Music Player

## Overview
This app allows users to browse and play music from their playlist.

Development Involved:
*  Identifying and implementing the use cases, behaviors, and features of a Jukebox
*  Implementing all the required layers step-by-step using test-driven development

  #### Conceptual Overview of a JukeBox: 
  ![crio-do-learn-portfolio-skm4898-ME_OBJECT_MODELING_V2-me-objectmodeling-milestone-1](https://github.com/SoumyaMehta/Object-Modeling/assets/69056406/7c8a743b-8886-4ed9-a6b5-50546ac0d0e7)


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

