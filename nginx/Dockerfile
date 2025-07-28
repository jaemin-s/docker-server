FROM nginx:1.27.2-alpine
COPY ./myserver.conf /etc/nginx/conf.d/myserver.conf
RUN rm /etc/nginx/conf.d/default.conf

EXPOSE 80
CMD ["nginx","-g","daemon off;"]
