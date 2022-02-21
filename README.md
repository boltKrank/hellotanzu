# hellotanzu

Springboot app that prints "Hello Tanzu!" from a containerised webserver

Command to build image:

./gradlew bootBuildImage --imageName=hellotanzu/spring-boot-docker

To run:

docker run -p 8080:8080 hellotanzu/spring-boot-docker
