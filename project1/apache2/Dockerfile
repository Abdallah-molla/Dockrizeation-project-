# Use the official Apache HTTP Server image from the Docker Hub
FROM httpd:latest

# Copy your local HTML files or application to the container's web root
# This example assumes you have a local 'html' folder with your web files

# Copy your local HTML files or application to the container's web root
# This example assumes you have a local 'html' folder with your web files
COPY index.html /usr/local/apache2/htdocs/

# Expose port 80 (default port for Apache HTTP server)
#EXPOSE 80

# Start Apache in the foreground
CMD ["httpd-foreground"]


