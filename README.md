# Fastify Docker Setup Project

This is a simple project intended to familiarize you with setting up Docker and using the Fastify framework.

## Getting Started

Follow the instructions below to get started with this project.

### Prerequisites

- Docker
- Node.js
- npm

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/fastify-docker-setup.git
    ```
2. Navigate to the project directory:
    ```sh
    cd fastify-docker-setup
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

### Running the Project

1. Build the Docker image:
    ```sh
    docker build -t fastify-docker-setup .
    ```
2. Run the Docker container:
    ```sh
    docker run -p 3000:3000 fastify-docker-setup
    ```

### Usage

Access the Fastify server by navigating to `http://localhost:3000` in your web browser.

## Contributing

Feel free to submit issues or pull requests if you find any bugs or have suggestions for improvements.

## License

This project is licensed under the MIT License.