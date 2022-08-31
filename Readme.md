Change Vars at your ...
ENV PGPASSWORD="welkom01"
ENV LANG="en_US.utf8"
ENV PG_MAJOR="14"
ENV PG_VERSION="14.5"
ENV PGUSER="postgres"
ENV PGDATA="/pg02/${PG_MAJOR}/data"
ARG PG_EXTENSION="tar.gz"
ARG PGBIN="/pg01/${PG_MAJOR}/${PG_DIR}"
ARG PGDIR2="/pg03/${PG_MAJOR}/archive"
ARG PGDIR3="/pg04/${PG_MAJOR}/"
ARG PG_HOME="${PGBIN}"
ARG PG_EXTENSION="tar.gz"
ARG TZ="Europe/amsterdam"


There will be more 
