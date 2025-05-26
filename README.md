# Docker Playground

A collection of Docker-based development environments and examples for various web technologies. This repository serves as a learning resource and starting point for containerized web applications.

## Projects

This repository contains several Docker-based projects:

- **starter-next-docker**: A Next.js application with Docker configuration
- **mern-docker**: MERN stack (MongoDB, Express, React, Node.js) application with Docker setup
- **hello-docker**: Basic Docker example for beginners
- **vite-project**: Vite-based React application with Docker configuration
- **react-docker**: React application with Docker setup
- **next-docker**: Next.js application with Docker configuration

## Getting Started

Each project in this repository is self-contained and includes its own Docker configuration. To get started with any project:

1. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```

2. Build the Docker image:
   ```bash
   docker build -t <project-name> .
   ```

3. Run the container:
   ```bash
   docker run -p <host-port>:<container-port> <project-name>
   ```

## Prerequisites

- Docker installed on your system
- Docker Compose (optional, for multi-container setups)
- Git for cloning the repository

## Project Structure

Each project follows a similar structure:
- `Dockerfile`: Contains instructions for building the Docker image
- `docker-compose.yml`: (where applicable) Defines multi-container Docker applications
- Application-specific files and configurations

## Contributing

Feel free to contribute to this repository by:
1. Forking the repository
2. Creating a new branch for your feature
3. Submitting a pull request

## License

This project is open source and available under the MIT License.

## Resources

- [Docker Documentation](https://docs.docker.com/)
- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://reactjs.org/docs)
- [Vite Documentation](https://vitejs.dev/guide/) 