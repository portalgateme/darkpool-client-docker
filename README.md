# darkpool-client-docker

## Getting Started

1. **Create Your Configuration File**  
   Copy the example configuration file to create your own configuration:
   ```bash
   cp data/config.yaml.example data/config.yaml
   ```

2. **Start the Service**  
   Use Docker Compose to start the service in detached mode:
   ```bash
   docker-compose up -d
   ```

3. **Access the Service**  
   The service will be available at `http://localhost:3002`.
   Port could be changed at docker-compose.yml
