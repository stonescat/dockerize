# kafka

## kafka.yaml
- kafka集群在k8s上helm部署
- `helm repo add bitnami https://charts.bitnami.com/bitnami`
- `helm -n infra install kafka -f kafka.yaml bitnami/kafka --version 10.3.3`
