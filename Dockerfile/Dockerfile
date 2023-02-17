FROM jenkins/jenkins:lts
USER root
RUN apt update -y
RUN apt install -y make
RUN apt install -y g++
# drop back to the regular jenkins user - good practice
USER jenkins






