FROM fluent/fluentd:v1.14.6-debian-1.1
USER root
RUN ["gem", "install", "elasticsearch", "--version", "8.3.0"]
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.2.3"]
USER fluent