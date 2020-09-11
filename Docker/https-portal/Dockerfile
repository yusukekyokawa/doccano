FROM steveltn/https-portal:1
RUN sed -i 's/daily/monthly/' /etc/logrotate.d/nginx
# RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d
