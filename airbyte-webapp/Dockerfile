ARG NGINX_IMAGE=nginx:1.25.3-alpine3.18
FROM ${NGINX_IMAGE} as webapp

EXPOSE 80

COPY bin/build /usr/share/nginx/html
COPY bin/nginx/default.conf.template /etc/nginx/templates/default.conf.template
