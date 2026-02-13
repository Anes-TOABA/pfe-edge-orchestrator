# Use the lightweight Nginx image
FROM nginx:alpine

# Remove the default Nginx welcome page
RUN rm -rf /usr/share/nginx/html/*

# Copy our custom HTML into the image
COPY index.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80
