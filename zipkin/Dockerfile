FROM openjdk:latest
ENV PROJECT_PATH=/usr/share/zipkin
RUN mkdir -p $PROJECT_PATH
COPY ./app $PROJECT_PATH
WORKDIR $PROJECT_PATH
ENTRYPOINT java -jar /usr/share/zipkin/zipkin.jar
