# kube-prometheus-stack helm reposu, alertmanager'ın proxy ayarları yapılarak slack alert yollanması, values.yaml ektedir
```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
```
```
helm upgrade --install monitoring-stack prometheus-community/kube-prometheus-stack -n monitoring --values helm-values.yaml
```