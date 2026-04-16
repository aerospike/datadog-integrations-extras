FROM ruby:latest@sha256:807b8f3d32280ca472bbc0a270fb34672c65e82c4096b84252894596b36e530f

COPY script.sh /opt/local/script.sh

RUN chmod 755 /opt/local/script.sh

RUN gem install nats

CMD ["/opt/local/script.sh"]
