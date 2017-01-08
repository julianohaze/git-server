FROM nginx:latest

ADD files/conf.d/* /etc/nginx/conf.d/
#ADD ./files/nginx.conf /etc/nginx/nginx.conf

VOLUME [ "/var/log/nginx" ]

EXPOSE 80
