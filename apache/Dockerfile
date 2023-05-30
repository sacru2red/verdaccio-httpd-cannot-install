FROM httpd:2.4.57

COPY ./apache/httpd.conf /usr/local/apache2/conf/httpd.conf
COPY ./apache/httpd-vhosts.conf /usr/local/apache2/conf/extra/httpd-vhosts.conf

# toggle it
# RUN sed -i "s@# AddEncoding x-gzip .gz .tgz@AddEncoding x-gzip .gz .tgz@g" /usr/local/apache2/conf/httpd.conf
