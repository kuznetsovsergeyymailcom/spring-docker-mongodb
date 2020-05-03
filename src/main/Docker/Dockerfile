FROM openjdk

VOLUME /tmp
ADD maven/spring-boot-mongodb-0.0.3-SNAPSHOT.jar myapp.jar
RUN sh -c 'touch /myapp.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/myapp.jar"]
