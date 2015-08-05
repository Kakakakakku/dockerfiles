FROM centos:centos6
MAINTAINER Yoshiaki Yoshida <y.yoshida22@gmail.com>

ADD etc/nginx.repo /etc/yum.repos.d/nginx.repo

RUN yum install -y nginx
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
