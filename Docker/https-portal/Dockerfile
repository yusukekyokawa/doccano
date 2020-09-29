FROM steveltn/https-portal:1
RUN sed -i 's/daily/monthly/' /etc/logrotate.d/nginx
RUN apt update
RUN apt install -y curl
RUN apt install -y lsof
# RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/conf.d
# 
# RUN rm /etc/nginx/conf.d/default.conf
# COPY nginx.conf /etc/nginx/conf.d
