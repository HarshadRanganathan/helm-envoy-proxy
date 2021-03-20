# helm-envoy-proxy

Example chart to install envoy proxy in your kubernetes cluster.

Chart Reference - https://github.com/helm/charts/tree/master/stable/envoy

|File|Description|
|--|--|
|configs/grpc-values.yaml | Sample config for proxying to a GRPC upstream server over TLS|

## Install/Upgrade Chart

Sample command to install (or) upgrade the chart -

```bash
helm upgrade -i envoy . -n platform --values=configs/grpc-values.yaml
```
