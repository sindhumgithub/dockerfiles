FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
COPY qi/ /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"] 
EXPOSE 80/tcp