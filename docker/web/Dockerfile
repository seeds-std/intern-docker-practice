FROM seedsstd/seeds_amznlinux2_lamp:7.4

COPY virtual.conf /etc/httpd/conf.d/virtual.conf
COPY php.ini /etc/php.d/php.ini

CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]
