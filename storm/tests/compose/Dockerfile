FROM maven:3.5.0-jdk-7@sha256:4b18a7ccf2d4b8150452e65411d15fef102fce4c02975ea7c670e122404d4fda


RUN curl -fsSL https://github.com/apache/storm/archive/v1.2.3.tar.gz -o storm.tar.gz \
    && tar -xf storm.tar.gz \
    && cd storm-*/examples/storm-starter \
    && mvn -Dmaven.test.skip=true package \
    && mv target/storm-starter-*.jar /topology.jar

ENTRYPOINT ["/bin/sleep"]
CMD ["120"]
