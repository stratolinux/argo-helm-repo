# Argo Helm Repository

This repository contains a collection of Helm charts following the app-of-apps model for Kubernetes deployments.

## Charts

The repository contains the following Helm charts:

- [addons](charts/addons/README.md) - A Helm chart for basic K8s services
- [addons-config](charts/addons-config/README.md) - A Helm chart for basic K8s services (configuration)
- [developer](charts/developer/README.md) - A Helm chart for development tools
- [static-volumes](charts/static-volumes/README.md) - A Helm chart for statically provisioned volumes

## Overview

This collection of Helm charts is designed to provide a comprehensive set of applications and services for Kubernetes clusters. Each chart is structured to follow best practices and can be customized through values files to suit specific deployment requirements.

The charts are organized to support a layered approach to cluster management:
- Addons: Core infrastructure services
- Addons-Config: Configuration for addons
- Developer: Development tools and environments
- Static Volumes: Storage solutions for static volumes

## Usage

To use these charts, add this repository to your Helm configuration:

```bash
helm repo add argo-helm https://stratolinux.github.io/argo-helm-repo
```

Then install any of the charts:

```bash
helm install my-addon argo-helm/addons
```

For detailed configuration options, please refer to the individual chart README files listed above.
