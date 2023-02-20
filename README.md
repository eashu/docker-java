# docker-java
About running Java in Docker container.

$ git clone https://github.com/mkyong/docker-java

$ cd docker-java-app

$ mvn package

$ java -jar target/find-links.jar https://google.com

//dockerize
// create a docker image
$ sudo docker build -t docker-java:1.0 .

// run it
$ sudo docker run -t docker-java:1.0 https://google.com

