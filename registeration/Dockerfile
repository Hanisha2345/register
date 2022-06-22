FROM openjdk:8
COPY src/devops/registerationform.java /tmp
WORKDIR /tmp
RUN ["javac","registerationform.java"]
ENTRYPOINT ["java","registerationform"]
