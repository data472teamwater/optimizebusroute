# Use an official Nginx image as the base
FROM nginx:alpine

# Copy the static HTML file to the Nginx html directory
COPY index.html /usr/share/nginx/html/

# Expose port 80 to the outside world
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
