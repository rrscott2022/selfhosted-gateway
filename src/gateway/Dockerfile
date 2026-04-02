FROM nginx

ENV CLIENT_MAX_BODY_SIZE=500M

# Dynamic HTTP
ADD http.conf.template /etc/nginx/templates/http.conf.template
# Dynamic HTTPS(SNI)
ADD nginx.conf.template /etc/nginx/templates/nginx.conf.template
