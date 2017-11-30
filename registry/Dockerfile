FROM registry:2.0
RUN mkdir /certs
RUN openssl req -newkey rsa:4096 -nodes -sha 256 -keyout certs/domain.key -x509 -days 365 -out certs/domain.certs