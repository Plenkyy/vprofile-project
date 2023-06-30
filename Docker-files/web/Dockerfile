FROM nginx
LABEL project="project"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY vprofile-project/Docker-files/web/nginxvproapp.conf /etc/nginx/conf.d/vproapp.conf
