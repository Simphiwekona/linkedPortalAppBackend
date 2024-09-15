FROM ubuntu:latest
LABEL authors="simphiwe"

# Use the official Keycloak image from the Docker Hub
FROM quay.io/keycloak/keycloak:22.0.5

# Optionally, copy custom configuration or add your own files
# COPY custom-config.json /opt/jboss/keycloak/standalone/configuration/

# Set environment variables for Keycloak
ENV KEYCLOAK_ADMIN=admin
ENV KEYCLOAK_ADMIN_PASSWORD=admin
