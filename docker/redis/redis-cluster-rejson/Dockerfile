FROM redislabs/rejson:2.6.8 as rejson
FROM docker.io/bitnami/redis-cluster:7.2.4
COPY --from=rejson /usr/lib/redis/modules/rejson.so /usr/local/lib/rejson.so
WORKDIR /opt/bitnami
