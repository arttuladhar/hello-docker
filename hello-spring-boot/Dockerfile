FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp

EXPOSE 8080

ADD build/libs/sample-api-*.jar sample-api.jar
RUN sh -c 'touch /sample-api.jar'

ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -jar /sample-api.jar" ]
