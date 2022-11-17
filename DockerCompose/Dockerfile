FROM    centos:7
RUN yum update -y && yum install httpd httpd-tools -y
EXPOSE  80
#Since services don't run in containers, just applications, we will manually launch httpd in the foreground
CMD     ["/usr/sbin/httpd","-D","FOREGROUND"]