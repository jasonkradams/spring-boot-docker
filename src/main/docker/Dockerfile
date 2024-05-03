FROM amazoncorretto:21-alpine-jdk

VOLUME /tmp
ARG FILENAME
ENV fileName=$FILENAME
ADD maven/${FILENAME}.jar /${FILENAME}.jar
ENTRYPOINT java -jar /${fileName}.jar