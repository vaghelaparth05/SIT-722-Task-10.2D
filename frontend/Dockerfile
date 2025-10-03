FROM nginx:alpine

# Replace default server config
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Static site (index.html, main.js, assets, etc.)
COPY . /usr/share/nginx/html

EXPOSE 80
CMD ["nginx","-g","daemon off;"]