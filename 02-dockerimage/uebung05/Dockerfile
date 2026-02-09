# Use the latest Alpine image
FROM alpine:3.23.3

LABEL Author="Julian Schleyben" 
# Update the package index and install Python 3.12 and pip
RUN apk add --no-cache python3
RUN apk add --no-cache py3-pip

# Set the working directory
WORKDIR /app

CMD ["python3"]