FROM openjdk:netcat
RUN mkdir -p /usr/local/configserver
ADD  configurationserver-1.0-SNAPSHOT.jar /usr/local/configserver/
ADD run.sh run.sh
RUN chmod +x run.sh
CMD ./run.sh
