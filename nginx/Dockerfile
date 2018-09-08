FROM opendns/nginx-auth-proxy

ADD nginx.conf /usr/local/nginx/conf/nginx.conf
ADD nginx.default /usr/local/nginx/conf/sites-enabled/default.template

CMD /start.sh

# docker run \
#   -e AUTH_BACKEND=https://someauthapi \
#   -e BACKEND=https://youprivateregistry \
#   -p 0.0.0.0:8080:80 nginx-auth

# FROM nginx:1.13

# ADD proxy.conf.tpl /etc/nginx/conf.d/default.conf.tpl
# ADD start.sh /start

# RUN ["chmod", "+x", "/start"]

# CMD ["/start"]
