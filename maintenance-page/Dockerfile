# Use the official Nginx image as the base image
FROM nginx:stable-alpine



# Copy your HTML and JSON files to the Nginx document root
COPY index.html usr/share/nginx/html/index.html
COPY sorry.json usr/share/nginx/html/sorry.json

# Expose port 80 for HTTP traffic
EXPOSE 80

# Start Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
