FROM nginx:latest

# Remove the default NGINX index page
RUN rm -rf /usr/share/nginx/html/*
# Set correct ownership for NGINX to access the files

RUN chown -R nginx:nginx /usr/share/nginx/html
# Copy your web app files into the NGINX web directory

COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]


