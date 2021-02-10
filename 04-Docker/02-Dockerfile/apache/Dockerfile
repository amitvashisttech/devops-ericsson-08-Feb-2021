# Base Image
FROM ubuntu:16.04

# Mainteiner of this IMAGE
MAINTAINER Amit Vashist <amitvashist7@outlook.com>

# Initialize APT Repo
RUN apt-get update

# Install Apache Packages 
RUN apt-get install apache2 -y 

# Custom Web Page
COPY amit.html /var/www/html/index.html

# My App will listen on the following Port
EXPOSE 80
EXPOSE 3306

# Run the Apache Service
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
