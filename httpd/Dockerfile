FROM centos:centos6
MAINTAINER Yoshiaki Yoshida <y.yoshida22@gmail.com>

RUN yum install -y httpd
EXPOSE 80
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]
