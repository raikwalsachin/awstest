FROM centos:7
RUN yum -y install epel-release
RUN yum -y install nginx
COPY nginx.conf /etc/nginx/nginx.conf
ADD ssl /etc/nginx/ssl 

CMD ["nginx", "-g", "daemon off;"]

EXPOSE 443
