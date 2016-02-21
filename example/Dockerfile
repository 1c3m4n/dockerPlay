FROM java:8-jre
MAINTAINER Joshua <potgieter.josh@gmail.com>

COPY ../builds/example/*.jar /app/
COPY entry.sh /app/entry.sh
RUN chmod 755 /app/entry.sh

ENTRYPOINT /app/entry.sh

