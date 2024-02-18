FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY roboshop.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/

# 2 RUN RM -RF for deleting default nginx index.html
# 3 RUN RM -RF for deleting default nginx config

# Now when you start web cantainer Nginx will be started automatically  