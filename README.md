# ntpd
This repo contains configuration files for building a dockerized ntp daemon using alpine linux

# docker
docker run --cap-add SYS_TIME --restart=always -d fbotha/ntpd
