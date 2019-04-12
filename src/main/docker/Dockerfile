FROM postgres:11
VOLUME ["/var/log/postgresql"]
COPY createschema.sql /docker-entrypoint-initdb.d/
