# syntax=docker/dockerfile:1

ARG NODE_VERSION

FROM node:${NODE_VERSION}-slim as base
WORKDIR /app

# Install AWS CDK globally
RUN npm install -g aws-cdk

# Copy your CDK project files to the container
COPY . .