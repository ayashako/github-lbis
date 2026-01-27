# Use official ubuntu image
FROM ubuntu

# Remove default nginx website
RUN apt update
RUN apt install nginx -y

# Copy your static files to nginx folder


# Expose port 80 & 8080
EXPOSE 80
EXPOSE 8080

# Start nginx
CMD ["nginx", "-g", "daemon off;"]

