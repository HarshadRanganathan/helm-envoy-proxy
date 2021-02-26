# helm-envoy-proxy

Example chart to install envoy proxy in your kubernetes cluster.

|||
|--|--|
|grpc-values.yaml | Sample config for proxying to a GRPC upstream server over TLS|

## Install/Upgrade Chart

To install (or) upgrade the chart -

```bash
helm upgrade -i envoy . -n platform --values=configs/grpc-values.yaml
```
