FROM nginx:latest
RUN mkdir -p /sr/nginx_cache
ADD ./statics /usr/share/nginx/html
ADD ./nginx.conf /etc/nginx/nginx.conf