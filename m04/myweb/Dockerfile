#Servidor web
FROM juan22/mydebian22:latest
label author="@juan22"
label curs="m14 22-23"
run apt-get update && apt-get install -y procps iproute2 iputils-ping nmap tree vim apache2
COPY index.html /var/www/hmtl
WORKDIR /tmp
EXPOSE 80
CMD apachectl -k start -X
