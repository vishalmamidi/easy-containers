# Use the official Ubuntu image as the base
FROM ubuntu:22.04

# Update the package list and install required packages
RUN apt-get update && apt-get install -y \
    unzip \
    nmap \
    netcat \
    curl \
    telnet \
    iputils-ping \
    dnsutils \
    && rm -rf /var/lib/apt/lists/*

# Set the default command
CMD ["bash"]
