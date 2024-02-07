FROM mysql:8.0.33 as DB_IMAGE
LABEL "Project"="Vprofile"
LABEL "Author"="Chirram Kumar"

ENV MYSQL_ROOT_PASSWORD="SAMPLE"
ENV MYSQL_DATABASE="accounts"

COPY db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql