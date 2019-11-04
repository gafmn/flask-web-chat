FROM mongo:4.2

COPY docker-entrypoint.sh /

ENTRYPOINT ["/docker-entrypoint.sh"]

CMD ["/usr/bin/mongod", "--bind_ip_all", "--replSet", "rs0"]