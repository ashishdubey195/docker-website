FROM nginx

COPY wrapper.sh /

COPY html /usr/share/nginx/html

RUN chmod +x wrapper.sh

EXPOSE 80

ENTRYPOINT ["/wrapper.sh"]
