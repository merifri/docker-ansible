FROM debian:buster-slim

RUN apt-get update && apt-get -y install python git openssh-client --no-install-recommends
RUN apt-get -y install python-pip
RUN pip install --upgrade pip && pip install ansible==2.4.1

CMD ["/bin/bash"]
