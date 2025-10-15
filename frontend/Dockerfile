# Use official Nginx image
FROM nginx:alpine

# Set working directory inside container
WORKDIR /usr/share/nginx/html

# Remove default Nginx files
RUN rm -rf ./*

# Copy your HTML/CSS website files to Nginx web root
COPY . .

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
