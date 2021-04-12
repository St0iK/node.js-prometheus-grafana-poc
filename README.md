# Node.js Application Monitoring with Prometheus and Grafana

The repository contains a sample Node.js app which integrates the [Prometheus client for node.js](https://github.com/siimon/prom-client) and exposes metrics on [http://localhost:8080/metrics](http://localhost:8080/metrics). The metrics are periodically scraped by [Prometheus](https://prometheus.io) and visualized through a [Grafana](https://grafana.com/oss/grafana) monitoring dashboard.

## Getting started

 Start the Docker containers:
```bash
docker-compose up -d
```

## Test containers
- Prometheus should be accessible via [http://localhost:9090](http://localhost:9090)
- Grafana should be accessible via [http://localhost:3000](http://localhost:3000)
- Example Node.js server metrics for RED monitoring should be accessible via [http://localhost:8080/metrics](http://localhost:8080/metrics)

## Open monitoring dashboards
Open in your web browser the monitoring dashboards:
- Monitoring dashboard for the Node.js app can be found on[http://localhost:3000/d/1DYaynomMk/example-service-dashboard](http://localhost:3000/d/1DYaynomMk/example-service-dashboard)
