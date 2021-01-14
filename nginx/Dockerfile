FROM nginx
COPY nginx.conf.t1 /etc/nginx/conf.d/default.conf
EXPOSE 80/tcp
RUN chmod 644 /etc/nginx/conf.d/default.conf
RUN chown root.root /etc/nginx/conf.d/default.conf
RUN service nginx start
