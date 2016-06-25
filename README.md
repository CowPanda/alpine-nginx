
##### Usage
    docker run -d --name mynginx -v \
    /yourpath:/usr/share/nginx/html \
    -p 3000:80 cowpanda/alpine-nginx:latest
