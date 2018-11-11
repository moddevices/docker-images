FROM ubuntu:18.04
MAINTAINER Alexandre Cunha <ale@moddevices.com>

# update and upgrade system
RUN apt-get update && apt-get -qy upgrade && apt-get clean

# install basic build tools
RUN apt-get install -qy build-essential ca-certificates \
    ssh git subversion curl bzip2 nano unzip

CMD ["bash"]