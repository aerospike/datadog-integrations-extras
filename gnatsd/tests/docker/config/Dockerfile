FROM ruby:latest@sha256:5802efab3a48c79ebcacd19c3b81ef545a7b5cf04d8b441247397f05bb720883

COPY script.sh /opt/local/script.sh

RUN chmod 755 /opt/local/script.sh

RUN gem install nats

CMD ["/opt/local/script.sh"]
