
FROM frolvlad/alpine-oraclejdk8
VOLUME /tmp
ADD  target/demo-0.0.1-SNAPSHOT.jar demo.jar
EXPOSE 8090
ENTRYPOINT ["java","-jar","/demo.jar"]
