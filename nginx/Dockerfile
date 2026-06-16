FROM nginx:alpine

# Копируем кастомный конфиг, заменяя стандартный
COPY default.conf /etc/nginx/conf.d/default.conf

# Копируем страницу ошибки
COPY 50x.html /usr/share/nginx/html/50x.html

EXPOSE 80

# Запуск nginx в foreground-режиме
CMD ["nginx", "-g", "daemon off;"]