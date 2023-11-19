# Docker Swarm Setup Script

This script automates the installation of Docker and Docker Compose on an Ubuntu system. It also initializes a Docker Swarm with the host's IP address.

## Prerequisites

- The script assumes you are running an Ubuntu-based system.
- Ensure that you have administrative privileges.

## Usage

1. Open a terminal.

2. Make the script executable:

    ```bash
    chmod +x setup-docker.sh
    ```

3. Run the script:

    ```bash
    ./setup-docker.sh
    ```

4. Follow any prompts during the installation process.

5. After the script completes, Docker and Docker Compose should be installed, and a Docker Swarm will be initialized.

## Script Details

- The script updates the package list and installs necessary dependencies.
- Adds Docker's GPG key and sets up the Docker repository.
- Installs Docker, Docker Compose, and related plugins.
- Creates a 'docker' group and adds the current user to it.
- Initializes a Docker Swarm using the host's IP address.
