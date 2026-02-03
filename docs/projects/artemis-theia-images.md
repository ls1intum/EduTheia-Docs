---
title: Artemis Theia Images
sidebar_label: IDE Images
---

# Overview

The **Artemis Theia Images** repository manages the Docker builds for custom Eclipse Theia IDE instances. These images are pre-configured with the specific tools, plugins, and settings required for student exercises on the Artemis platform.

## Key Features

- **Customized IDEs**: Tailored environments for different programming languages (Java, C, Python, etc.).
- **Optimized Build Process**: Uses multi-stage Docker builds to ensure small and efficient production images.
- **Security-First**: Configured to run as a non-root `theia` user for better container security in cloud environments.
- **Plugin Integration**: Includes pre-installed VS Code extensions and Theia plugins necessary for the educational ecosystem.

## Tech Stack

- **Docker**: Containerization and image management.
- **Node.js**: The underlying runtime for the Theia application.
- **Eclipse Theia**: The core IDE framework used as the base for these images.

## Repository Link

[ls1intum/artemis-theia-images](https://github.com/ls1intum/artemis-theia-images)
