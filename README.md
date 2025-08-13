# Kong Security

This repository provides a sample configuration for a secure Kong Gateway setup.

## Getting Started

To get started with this project, you need to have Docker and Docker Compose installed.

1. Clone this repository:

   ```sh
   git clone https://github.com/shukawam/kong-security.git
   ```

2. Create `.env`:

    ```sh
    cp .env.example .env
    ```

3. Start the services:

   ```sh
   docker-compose up -d
   ```

## Usage

The following services are available:

- **Kong Gateway:** [http://localhost:8000](http://localhost:8000)
- **Kong Admin API:** [http://localhost:8001](http://localhost:8001)
- **Kong Manager:** [http://localhost:8002](http://localhost:8002)
- **Grafana:** [http://localhost:3000](http://localhost:3000)

## Contributing

Contributions are welcome! Please feel free to submit a pull request.
