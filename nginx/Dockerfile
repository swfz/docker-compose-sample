#FROM centos:centos6
FROM nginx
MAINTAINER swfz sawafuji.09@gmail.com

#RUN rpm -Uhv http://dl.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm
#RUN yum update -y

#RUN yum install -y nginx

#COPY nginx.conf /etc/nginx/nginx.conf

COPY ["./nginx.conf", "/etc/nginx/nginx.conf"]

CMD ["/usr/sbin/nginx", "-g", "daemon off;"]
