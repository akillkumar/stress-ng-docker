# Use a base image with stress-ng preinstalled
FROM ubuntu:latest

# Install stress-ng
RUN apt-get update && apt-get install -y stress-ng

# Run stress-ng with disk I/O stress
CMD ["stress-ng", "--hdd", "1", "--hdd-bytes", "1G"]
