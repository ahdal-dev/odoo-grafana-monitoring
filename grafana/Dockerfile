FROM grafana/grafana:11.3.0

# Provision the repository's Odoo dashboards into the Grafana server image.
COPY provisioning/dashboards.yaml /etc/grafana/provisioning/dashboards/dashboards.yaml
COPY dashboards/ /var/lib/grafana/dashboards/

EXPOSE 3000
