FROM ubuntu:14.04
MAINTAINER Alexandre Cunha <alex@moddevices.com>
ENV DEBIAN_FRONTEND noninteractive

# update and upgrade system
RUN apt-get update && apt-get -qy upgrade && apt-get clean

# install basic build tools
RUN apt-get install -qy build-essential ca-certificates \
    ssh git subversion curl bzip2 nano unzip

CMD ["bash"]