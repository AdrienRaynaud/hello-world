FROM my-image-java

RUN mkdir /opt/helloworld
COPY helloworld.jar /opt/helloworld/
ENTRYPOINT ["java", "-jar", "/opt/helloworld/helloworld.jar"]
