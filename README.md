# Docker PHP Project

This repository contains a Docker project for a PHP application.

## Description

The Docker PHP Project provides a development environment for running a PHP application using Docker containers. It includes a PHP Apache environment and a MySQL database container.

## Features

- PHP Apache environment with preconfigured settings
- MySQL database container with preconfigured settings
- Easy setup and configuration using Docker Compose
- Customizable PHP and Apache settings
- Mount volumes for easy code and data persistence
- Separate containers for PHP and MySQL for better scalability and maintainability

## Prerequisites

Make sure you have the following prerequisites installed on your system:

- Docker
- Docker Compose

## Getting Started

1. Clone this repository to your local machine:
git clone https://github.com/mahmuda-bjit/Docker_php_project.git

2. Navigate to the project directory:
cd Docker-sample-web-app

3. There will be 3 files: conf, docker-compose.yaml, php, preview.png.

4. Start the containers using Docker Compose:
docker-compose up -d

5. Access the PHP application in your browser:
http://localhost:80

Or to run with virtual machine ip address, use your virtual machine's ip address, for example: http:192.168.**.**:80

## Configuration

The project can be further customized by modifying the configuration files:

- `Dockerfile`: Contains the Dockerfile for building the PHP Apache environment.
- `php.ini`: Contains the PHP configuration settings.
- `docker-compose.yml`: Contains the configuration for Docker Compose.
