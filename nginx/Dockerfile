# TODO заменить конфиг /etc/nginx/conf.d/default.conf и добавить 50x.html в соответствии с этим конфигом
FROM nginx:alpine
COPY default.conf /etc/nginx/conf.d/default.conf
RUN touch /usr/share/nginx/html/50x.html