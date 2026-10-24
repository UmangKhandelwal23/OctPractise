FROM ubuntu
RUN  apt-get update -y &&  apt-get install nginx -y
COPY . /var/www/html
ENTRYPOINT ["nginx","-g","daemon off;"]
