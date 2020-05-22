Bootstrap:docker
From: ubuntu:20.04

%post
apt-get update && \
apt-get install -y coq libssreflect-coq git curl wget &&\
apt-get clean

wget https://github.com/cdr/code-server/releases/download/v3.3.1/code-server_3.3.1_amd64.deb
dpkg -i code-server_3.3.1_amd64.deb

%runscript
code-server "$@"


