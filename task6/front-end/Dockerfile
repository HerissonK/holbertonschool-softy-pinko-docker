# Use the latest version of nginx
FROM nginx:latest

# Copy to /var/www/html/softy-pinko-front-end on the Docker image
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy to the Docker image to /etc/nginx/conf.d/default.conf
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
