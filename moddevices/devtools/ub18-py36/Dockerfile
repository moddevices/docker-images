FROM moddevices/devtools:ub18-essential
MAINTAINER Alexandre Cunha <ale@moddevices.com>

# install python3.4 and python dev tools
RUN apt-get install -qy python3 python3-dev python3-all-dev python3-pip python-virtualenv
RUN update-alternatives --install /usr/bin/python python /usr/bin/python3 10
RUN python -m pip install --upgrade pip

CMD ["bash"]
