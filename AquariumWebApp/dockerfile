# lightweight nginx iamge
FROM nginx:alpine

# Remove the default Nginx static files
RUN rm -rf /usr/share/nginx/html/*

# copy the static site files into NGINX web root
COPY . /usr/share/nginx/html

# Expose port 80 for HTTP traffic
EXPOSE 80

# Decaulft NGINX CMD is already set by base Image