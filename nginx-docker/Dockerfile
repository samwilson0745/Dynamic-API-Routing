# Use the official Nginx image
FROM nginx:alpine

# Copy the custom nginx.conf file to the container
COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 8080 to access the API Gateway
EXPOSE 8080

# Run Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]