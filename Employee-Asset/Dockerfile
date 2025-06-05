FROM nginx:alpine

# Remove default nginx page and copy your own
RUN rm -rf /usr/share/nginx/html/*
COPY index.html /usr/share/nginx/html/

EXPOSE 80

