* `minikube start`{{execute}}
* `docker pull zookeeper`
* `docker pull eitanya/kafka:0.11.0.2`
* `kubectl apply -f  https://eitan101.github.io/containers/manifests-examples/mykafka/k8s.yml`{{execute}}
* [open minikube dashboard](https://[[HOST_SUBDOMAIN]]-30000-[[KATACODA_HOST]].environments.katacoda.com/)
* Scale and inspect logs using the dashboard