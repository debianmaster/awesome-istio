### to view updated envoy rules
```sh
curl localhost:15000/routes  #inside a pod which has istio-proxy sidecar
or
curl http://istio-pilot:8080/v1/routes/80/istio-proxy/ingress/
```
