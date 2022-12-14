FROM postgres:14

RUN su - postgres

RUN gosu postgres pg_resetwal -f /var/lib/postgresql/data
