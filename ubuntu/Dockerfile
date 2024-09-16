# Use a smaller base image
FROM ubuntu:22.04

# Update the package list and install required packages without recommendations
RUN apt-get update && apt-get install -y --no-install-recommends \
    unzip \
    nmap \
    netcat \
    curl \
    telnet \
    iputils-ping \
    dnsutils \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

# Set the default command
CMD ["bash"]
