FROM openjdk:8
ADD target/dockerImage-0.0.1-SNAPSHOT.jar dockerImage.jar
ENTRYPOINT ["java","-jar","/dockerImage.jar"]