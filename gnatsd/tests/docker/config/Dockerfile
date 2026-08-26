FROM ruby:latest@sha256:a5752fdd44a3dd5381e018daaa72735aa9fdf074625e9a6f9237137ddcefeb44

COPY script.sh /opt/local/script.sh

RUN chmod 755 /opt/local/script.sh

RUN gem install nats

CMD ["/opt/local/script.sh"]
