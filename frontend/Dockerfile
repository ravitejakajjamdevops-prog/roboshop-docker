FROM nginx:1.24.0
RUN rm -f /usr/share/nginx/html/index.html
RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/
COPY frontend-code /usr/share/nginx/html/
CMD ["nginx","-g","daemon off;"]
