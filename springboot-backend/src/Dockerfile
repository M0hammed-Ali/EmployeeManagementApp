#!/bin/bash

# Variables (customize as needed)
IMAGE_NAME=my-java-app
CONTAINER_NAME=my-java-app-container

# Build the Docker image
echo "Building Docker image..."
docker build -t $IMAGE_NAME .

# Stop and remove any existing container
echo "Cleaning up old containers..."
docker rm -f $CONTAINER_NAME 2>/dev/null || true

# Run the container
echo "Starting new container..."
docker run -d --name $CONTAINER_NAME -p 8080:8080 $IMAGE_NAME
