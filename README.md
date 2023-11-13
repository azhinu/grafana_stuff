# Grafana stuff

This repo contains some alerts from [Awesome Prometheus](https://samber.github.io/awesome-prometheus-alerts/) that have been adopted to Grafana, dashboards and message template in provisioning format.

### Alerts

These alerts are a slightly modified version of alerts from the [Awesome Prometheus] (https://samber.github.io/awesome-prometheus-alerts/) project. They are linked to the dashboards in this repo.

### Dashboards

Some dashboards are slightly modified, they have a `_mod` suffix.

### Message template

This repo contains a message template for RocketChat.
This template assumes that alerts have a `severity' label. Alerts with severity `info' don't have an `@all' tag to avoid extra notifications. It's also recommended to use this template with 2 contact points: one with resolved message and one without.

### Useful links

* [Grafana provisioning](https://grafana.com/docs/grafana/latest/administration/provisioning/)
* [Grafana alerts provisioning](https://grafana.com/docs/grafana/latest/alerting/set-up/provision-alerting-resources/file-provisioning/)


### Credits

* [Awesome Prometheus](https://samber.github.io/awesome-prometheus-alerts/)
* [Blackbox exporter dashboard](https://grafana.com/grafana/dashboards/14928-prometheus-blackbox-exporter/)
* [Clickhouse dashboard](https://grafana.com/grafana/dashboards/14192-clickhouse/)
* [MinIO dashboard](https://grafana.com/grafana/dashboards/13502-minio-dashboard/)
* [Percona dashboards](https://github.com/percona/grafana-dashboards/)
* [Node exporter dashborard](https://grafana.com/grafana/dashboards/1860-node-exporter-full/)
* [Prometheus dashboard](https://grafana.com/grafana/dashboards/3662)
* [RabbitMQ detailed dashboard](https://grafana.com/grafana/dashboards/4279)
* [RabbitMQ overview dashborad](https://grafana.com/grafana/dashboards/10991-rabbitmq-overview/)
* [Redis dashboard](https://grafana.com/grafana/dashboards/763)
