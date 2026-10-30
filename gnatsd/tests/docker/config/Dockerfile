FROM ruby:latest@sha256:dd87233ce44e8362fed00a1fd590c01e3dd8f8eb0001ea4a2c8a071388e9185b

COPY script.sh /opt/local/script.sh

RUN chmod 755 /opt/local/script.sh

RUN gem install nats

CMD ["/opt/local/script.sh"]
