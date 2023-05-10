FROM httpd:2.4
RUN mkdir /app/
COPY ./hw.html /app/
COPY ./httpd.conf /usr/local/apache2/conf/httpd.conf
RUN usermod -u 1001 www-data; groupmod -g 1001 www-data
EXPOSE 8000
