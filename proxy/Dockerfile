FROM nginx:1.11.5-alpine

MAINTAINER genDevOps

# Clean default sites
RUN rm -rf /etc/nginx/sites-enabled

# Add config
ADD config/nginx.conf /etc/config/nginx.conf

# Add ssl certs
ADD ssl/ /etc/nginx/ssl

# Ports
EXPOSE 443
