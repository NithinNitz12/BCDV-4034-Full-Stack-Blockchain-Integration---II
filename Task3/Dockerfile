# Use an Ubuntu base image
FROM ubuntu:latest

# Install Node.js and npm
RUN apt-get update && \
    apt-get install -y curl && \
    curl -sL https://deb.nodesource.com/setup_18.x | bash && \
    apt-get install -y nodejs

# Verify Node.js and npm installation
RUN node -v
CMD ["node", "-v"]
