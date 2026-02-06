# AFFINITY FINDER APPLICATION

## Description
This application allows users to create forms and collect responses from other users. Based on the collected data, the application uses the K-means clustering algorithm to group users with similar responses into affinity groups. This can be useful for identifying common interests or preferences among users.


## Compilation and Execution
This project uses Gradle as the build automation tool. To compile and run the application, you need to have Java 11 or higher and Gradle installed on your machine.

./gradlew run


## Useful commands
./gradlew build will build and run all the unit tests
./gradlew test: will run your unit tests.<br>
./gradlew jarAllDrivers: will create the jar inside the directory <project root>/build/libs with all drivers as jar 
./gradlew assembleDist: will create a .tar and a .zip (both contain the same) in the directory <project root>/build/distributions that contain the whole directory structure that will allow to install your project along with its dependencies in a machine without IDE (only with java 11 installed) and run it.  
./gradlew clean: will clean the compilation files and the created artifacts


### More info

Gradle application plugin
https://docs.gradle.org/current/userguide/application_plugin.html
