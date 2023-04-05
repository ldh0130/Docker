FROM centos:7

RUN yum -y install httpd php && yum clean all

ADD src.tar /var/www/html

VOLUME /vas/www/html /var/log/httpd

EXPOSE 80

ENTRYPOINT /usr/sbin/httpd -D FOREGROUND
