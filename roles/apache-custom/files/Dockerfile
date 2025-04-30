FROM debian:bullseye-slim
RUN apt update && apt install -y apache2
RUN echo "I Did it" > /var/www/html/index.html
CMD ["apache2ctl", "-D", "FOREGROUND"]

