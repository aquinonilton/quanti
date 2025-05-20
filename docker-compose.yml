docker-compose.yml
version: "3.9"

services:
  langflow:
    image: ghcr.io/logspace-ai/langflow:latest
    container_name: langflow
    ports:
      - "7860:7860"
    volumes:
      - ./data:/data
    environment:
      - LANGFLOW_ENV=production
