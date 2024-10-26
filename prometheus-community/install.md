## install + set service type
helm install prometheus prometheus-community/prometheus  --namespace prometheus --create-namespace --set server.service.type=LoadBalancer