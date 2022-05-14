# Vance Installation

Vance is composed of a set of APIs implemented as Kubernetes Custom Resource Definitions (CRDs) and a controller.

## Pre-requisites

- install a Kubernetes cluster
- install [KEDA]
- install [KEDA-http]

## Install with YAML files

### Install

```
kubectl apply -f deploy/vance-1.0.0.yaml
```

### Uninstall

```
kubectl delete -f deploy/vance-1.0.0.yaml
```

[keda]: https://keda.sh/docs/2.7/deploy/
[keda-http]: https://github.com/kedacore/http-add-on/blob/main/docs/install.md

