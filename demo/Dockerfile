
FROM centos:7

MAINTAINER tian

RUN yum install epel-release -y 

RUN yum install nginx -y

RUN echo "daemon off;" >> /etc/nginx/nginx.conf

EXPOSE 80

CMD /usr/sbin/nginx
