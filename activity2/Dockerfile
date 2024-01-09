FROM amazoncorretto:17-alpine-jdk
LABEL aurher="dhille"
LABEL project="learning"
ADD https://referenceapplicationskhaja.s3.us-west-2.amazonaws.com/spring-petclinic-3.1.0-SNAPSHOT.jar /dhille/spring-petclinic.jar
WORKDIR /dhille
EXPOSE 8080
CMD [ "java", "jar", "spring-petclinic-3.1.0-SNAPSHOT.jar"  ]

