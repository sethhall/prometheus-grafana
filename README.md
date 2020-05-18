# Automatic Prometheus and Grafana set up with Docker Compose

Before starting, edit the prometheus endpoints you will be scraping to the bottom
of the `prometheus/prometheus.yml` file.

Start it up with:

```bash
docker-compose up -d
```

Stop it with:

```bash
docker-compose down
```

If you want to delete the data volumes (this will delete your prometheus database
and anything else you've stored!):

```bash
docker-compose down -v
```
