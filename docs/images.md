# Container images

The project uses fixed versions of the official container images.

| Component | Container image |
|---|---|
| Prometheus | `prom/prometheus:v3.13.3` |
| Alertmanager | `prom/alertmanager:v0.34.1` |
| Grafana | `grafana/grafana:13.1.6` |
| Node Exporter | `prom/node-exporter:v1.12.1` |
| kube-state-metrics | `registry.k8s.io/kube-state-metrics/kube-state-metrics:v2.19.1` |

All images were verified with `docker manifest inspect`.