FROM ruby:latest@sha256:342dd3092e25f9d16fc2a5c48c5bb2d9a93717d4f900d005d6e088e2c45d3d19

COPY script.sh /opt/local/script.sh

RUN chmod 755 /opt/local/script.sh

RUN gem install nats

CMD ["/opt/local/script.sh"]
