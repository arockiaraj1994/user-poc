It's Spring Boot application.

Build Tool : Gradle

To Install Gradle use follwed link 

https://www.javacodegeeks.com/2013/04/how-to-install-gradle-2.html

To Run application

1. cd <application_root_dir>
2. run "./gradlew build && java -jar build/libs/gs-spring-boot-0.1.0.jar"

After build complete

Open your browser or HTTP client (Postman etc.)

Enter followed URL : http://localhost:8080/user

The response will : { "id" : "1", "name" : "xyz", "type" : "client" }

