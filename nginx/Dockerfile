FROM centos:latest
MAINTAINER 0.1 Tadashi Goto
ADD nginx.repo /etc/yum.repos.d/
RUN ["yum","-y","install","nginx"]
RUN ["systemctl","enable","nginx.service"]

