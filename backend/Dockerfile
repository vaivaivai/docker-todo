FROM openjdk:8-jre-alpine
LABEL maintainer="Benjamin Dahlmanns"
EXPOSE 8081
ENTRYPOINT ["/usr/bin/java", "-jar", "/usr/local/todo-backend/todo-backend.jar"]

ADD target/todo-backend.jar /usr/local/todo-backend/todo-backend.jar
