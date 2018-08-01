FROM nginx

COPY nginx.html /usr/share/nginx/html

ADD docker /usr/share/nginx/html

LABEL version=1

CMD nginx -g 'daemon off;'
