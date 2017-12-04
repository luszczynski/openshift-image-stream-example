FROM httpd-base:latest
COPY src/index.html /var/www/html
#USER apache
EXPOSE 80
ENTRYPOINT [ "/usr/sbin/httpd" ]
CMD [ "-D", "FOREGROUND" ]
