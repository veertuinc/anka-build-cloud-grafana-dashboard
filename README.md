# Anka Build Cloud Grafana Dashboard

You can find the JSON in the repo root as dashboard.json. 

- You need the [Anka Build Cloud](https://docs.veertu.com/anka/anka-build-cloud/) and [Prometheus Exporter](https://github.com/veertuinc/anka-prometheus-exporter) setup.
- You'll need to replace `d1adc39b-b062-4171-9f2b-cdc18afae7b7` with the UUID of your Prometheus DataSource. You can find the ID for your data source in the URL on the Connections > DataSource > Prometheus page in your Grafana. For example, ours is `http://grafana.veertu.com/connections/your-connections/datasources/edit/d1adc39b-b062-4171-9f2b-cdc18afae7b7/`.
- You'll want to change `controller.myOrg.com` to your controller URL.
