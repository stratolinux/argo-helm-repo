# operations-helm

![Version: 0.5.0](https://img.shields.io/badge/Version-0.5.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 0.2.0](https://img.shields.io/badge/AppVersion-0.2.0-informational?style=flat-square)

A Helm chart for Kubernetes Operational Management tools

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| prometheus.adminPassword | string | `"adminpassword"` |  |
| prometheus.ingress.enabled | bool | `true` |  |
| prometheus.ingress.hosts[0] | string | `"your.host.name"` |  |
| prometheus.namespace | string | `"kube-prometheus-stack"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.14.2](https://github.com/norwoodj/helm-docs/releases/v1.14.2)
