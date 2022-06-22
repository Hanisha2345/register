FROM openjdk:8
COPY src/registerationform.java /tmp
WORKDIR /tmp
RUN ["javac","registerationform.java"]
ENTRYPOINT ["java","registerationform"]