FROM ruby:latest@sha256:d9a5d26be31a40fb043069f816ba39139c1f38758aea530341eb7e2c153e4ab4

COPY script.sh /opt/local/script.sh

RUN chmod 755 /opt/local/script.sh

RUN gem install nats

CMD ["/opt/local/script.sh"]
