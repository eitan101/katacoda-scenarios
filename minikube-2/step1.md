
* `alias build-machine='docker run --rm -it -v $PWD:/my -w /my maven:3-jdk-9-slim'`{{execute}}
* `build-machine mvn -q archetype:generate`{{execute}} (filter: dropwizard-app (1.1), item #1, group: grp, artifactId:myapp)
* `cd myapp`{{execute}}
* `build-machine mvn -q package`{{execute}}
* `minikube start`{{execute}}
* `docker pull mysql`{{execute}}
* `kubectl apply -f  https://eitan101.github.io/containers/manifests-examples/k8s.yml`{{execute}}
* [open minikube dashboard](https://[[HOST_SUBDOMAIN]]-30000-[[KATACODA_HOST]].environments.katacoda.com/)
* `watch kubectl get pods`{{execute}}
* [open service page](https://[[HOST_SUBDOMAIN]]-30080-[[KATACODA_HOST]].environments.katacoda.com/)
* `wget https://eitan101.github.io/containers/manifests-examples/k8s.yml`{{execute}}
* `kubectl apply -f k8s.yml`{{execute}}
* `kubectl logs -f podname`{{execute}}
