FROM nginx:latest

# Remove the default NGINX index page
RUN rm -rf /usr/share/nginx/html/*

# Copy your web app files into the NGINX web directory
COPY ./saveweb2zip-com-pepeunchained-com /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]


