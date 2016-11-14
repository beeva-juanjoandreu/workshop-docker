FROM ubuntu

MAINTAINER genDevOps

# Add binaries
ADD artifacts/* /usr/bin

# Ports
EXPOSE 80

# Run
CMD ["api", "--listen", ":80"]
