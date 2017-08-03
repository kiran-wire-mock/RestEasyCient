# RestEasyCient

Bring up wiremock:

http://wiremock.org/docs/running-standalone/

start wire mock usign the below 
java -jar wiremock-standalone-2.7.1.jar

then mappings and __files will be created

Add student.json under mappings directory

Restart the wiremock

Hit service in the postman using http://localhost:8080/student/marks

you should get the marks