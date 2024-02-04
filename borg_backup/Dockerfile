ARG BUILD_FROM
FROM $BUILD_FROM

# Execute during the build of the image
ARG TEMPIO_VERSION BUILD_ARCH
RUN apk add --no-cache --update \
    borgbackup \
    openssh-client \
    openssh-keygen

RUN mkdir /root/.ssh
RUN chmod 700 /root/.ssh

