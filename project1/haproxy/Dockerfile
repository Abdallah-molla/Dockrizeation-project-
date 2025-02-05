# Use the official HAProxy image from Docker Hub
FROM haproxy:latest

# Copy your custom HAProxy configuration file into the container
# Make sure you have a custom haproxy.cfg file in your current directory
COPY haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg

# Expose the port that HAProxy will listen on (default HTTP port 80 and 443 for HTTPS)
EXPOSE 80
EXPOSE 8080

# Start HAProxy in the foreground
CMD ["haproxy", "-f", "/usr/local/etc/haproxy/haproxy.cfg"]

