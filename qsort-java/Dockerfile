FROM alpine:latest
WORKDIR /app
COPY QuickSort.java /app


RUN apk add openjdk8
ENV JAVA_HOME /usr/lib/jvm/java-1.8-openjdk
ENV PATH $PATH:$JAVA_HOME/bin

RUN javac QuickSort.java

ENTRYPOINT java QuickSort