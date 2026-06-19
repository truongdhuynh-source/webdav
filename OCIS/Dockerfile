FROM owncloud/ocis:latest

ENV OCIS_INSECURE=true

COPY ocis-config/ocis.yaml /etc/ocis/ocis.yaml

VOLUME ["/var/lib/ocis"]

EXPOSE 9200
