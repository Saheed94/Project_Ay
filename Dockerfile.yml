# Use the official NGINX image from the Docker Hub
FROM nginx:latest

# Set the working directory inside the container
WORKDIR /usr/share/nginx/html

# Copy the HTML files from your local machine to the NGINX container
COPY . .

# Expose port 80 to the host machine
EXPOSE 80

# Command to run NGINX in the foreground
CMD ["nginx", "-g", "daemon off;"]

