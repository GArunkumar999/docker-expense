FROM nginx:latest
RUN rm -rf /usr/share/nginx/html/index.html
COPY code  /usr/share/nginx/html/index.html
COPY nginx.conf /etc/nginx/nginx.conf
