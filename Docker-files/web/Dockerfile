FROM nginx
LABEL "Project"="Vprofile"
LABEL "Author"="Andrew"

RUN rm -rf /etc/nginx/conf.d/default.conf
RUN mkdir -p /etc/nginx/conf.d
COPY nginxvproapp.conf /etc/nginx/conf.d/vproapp.conf

