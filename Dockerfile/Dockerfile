FROM ubuntu
LABEL AUTHOR=Srini \
      WEBSITE=Crispy-2129_crispy_kitchen

RUN apt-get update -y
RUN apt-get install -y nginx
COPY 2129_crispy_kitchen /var/www/html/
CMD ["nginx", "-g", "daemon off;"]