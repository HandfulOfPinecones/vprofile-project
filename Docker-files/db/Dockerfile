FROM mysql:8.0.33
LABEL "Project"="vprofile"
LABEL "Author"="Patryk"

ENV MYSQL_ROOT_PASSWORD="vproddbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb./db_backup.sql
