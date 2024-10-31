FROM nginx

# Remove the default HTML directory and NGINX configuration file
RUN rm -rf /usr/share/nginx/html/* \
    && rm -f /etc/nginx/nginx.conf

# Copy your custom NGINX configuration
COPY nginx.conf /etc/nginx/nginx.conf
