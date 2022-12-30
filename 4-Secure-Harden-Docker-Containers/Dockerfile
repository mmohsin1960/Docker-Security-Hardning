FROM ubuntu:18.04


RUN groupadd -r mohsin && useradd -r -g mohsin mohsin
# create group                          group  user

RUN chsh -s /usr/sbin/nologin root
# change shell 

ENV HOME /home/mohsin

LABEL maintainer="Mohsin"
