# 🐳 Use the official Nginx base image
FROM nginx:alpine

# 📁 Copy custom HTML files into Nginx's default HTML directory
COPY website/ /usr/share/nginx/html/

# 📢 Expose port 80 to access the container via this port
EXPOSE 80

# 🧠 Use default CMD provided by nginx image (no need to redefine it)
