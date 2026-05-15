FROM ruby:latest@sha256:695fa7949aaea223b36719d7d3eca2fa6e00fe730c55a376423ed9fef00533ee

COPY script.sh /opt/local/script.sh

RUN chmod 755 /opt/local/script.sh

RUN gem install nats

CMD ["/opt/local/script.sh"]
