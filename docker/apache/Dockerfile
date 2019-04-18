FROM httpd:2.4-alpine
#COPY httpd.conf /usr/local/apache2/conf/
#RUN echo "localhost app.local" >> /etc/hosts
RUN apk update; \
    apk upgrade;

COPY app.conf /usr/local/apache2/conf/app.conf
RUN echo "Include /usr/local/apache2/conf/app.conf" \
    >> /usr/local/apache2/conf/httpd.conf
