To Build the jar file, go to the project package where pom.xml is there:

mvn package
java -jar target/sprg-0.0.1-SNAPSHOT.jar

To shutdown the application:

curl -X POST localhost:port/actuator/shutdown