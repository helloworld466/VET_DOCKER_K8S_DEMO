# Use the official Nginx base image from Docker Hub
FROM nginx:latest

# Copy your custom index.html to the container's web root directory
COPY index.html /usr/share/nginx/html/

# Expose port 80 for incoming HTTP traffic
EXPOSE 80

# Start the Nginx server when the container runs
CMD ["nginx", "-g", "daemon off;"]