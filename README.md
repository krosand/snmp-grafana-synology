# Monitoring Stack with Prometheus, Grafana, and SNMP Exporter

## Structure
- `docker-compose.yml`: Main Docker Compose file.
- `config/`: Configuration files for each service.
- `data/`: Persistent data volumes (excluded from version control).

## Getting Started
1. Clone the repository.
2. Create a `.env` file for sensitive environment variables:
   ```plaintext
   GF_SECURITY_ADMIN_USER=<logn>
   GF_SECURITY_ADMIN_PASSWORD=<password>

