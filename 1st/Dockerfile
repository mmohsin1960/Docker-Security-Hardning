FROM ubuntu:18.04

LABEL maintainer="Mohsin"

#adding user in container 
RUN groupadd -r mohsin && useradd -r -g mohsin mohsin

#Prevent access to root user / or other user
#chsh (Change Shell)
RUN chsh -s /usr/sbin/nologin root 

#Environment Variables
ENV home /home/mohsin
ENV DEBIAN_FRONTEND=noninteractive 
