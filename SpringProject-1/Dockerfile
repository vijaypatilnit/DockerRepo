FROM openjdk:17-jdk-alpine
COPY ./target/SpringProject-1.jar /usr/app/
WORKDIR /usr/app
RUN sh -c 'touch SpringProject-1.jar'
ENTRYPOINT [ "java","-jar","SpringProject-1.jar" ]
