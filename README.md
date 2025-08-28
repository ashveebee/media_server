# 🐳 Docker Media Server Stack

This repository contains a set of `docker-compose` files to quickly and easily deploy a full-featured media server stack. It includes popular services for managing and serving your movies, TV shows, and more.

The goal is to provide a simple, configurable, and maintainable setup using Docker.

## ✨ Features

* **Easy to Deploy**: Get a complete media server running with a single command.
* **Centralized Configuration**: All services are managed from a single `docker-compose.yml` file.
* **Persistent Data**: Uses Docker volumes to ensure your configuration and data persist across container restarts and updates.
* **Pre-configured Services**: Includes compose files for the most common media server applications.

## stack-services-logo-wall

## 📦 Services Included

This stack is pre-configured with the following services:

| Service | Port | Description |
| :--- | :--- | :--- |
| **Prowlarr** | `9696` | Indexer manager for Sonarr, Radarr, etc. |
| **Sonarr** | `8989` | TV show collection manager. |

## 🚀 Getting Started

Follow these instructions to get your media server up and running.

### 1. Prerequisites

* **Docker**: Make sure Docker is installed on your system. [Install Docker](https://docs.docker.com/get-docker/)
* **Docker Compose**: Make sure Docker Compose is installed. [Install Docker Compose](https://docs.docker.com/compose/install/)
