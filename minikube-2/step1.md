
* `alias build-machine='docker run --rm -it -v $PWD:/my -w /my maven:3-jdk-9-slim'`{{execute}}
* `build-machine mvn -q archetype:generate`{{execute}} (filter: dropwizard-app (1.1), item #1, group: grp, artifactId:myapp)
* `cd myapp`{{execute}}
* `build-machine mvn -q package`{{execute}}
* `minikube start`{{execute}}
* `docker pull mysql`{{execute}}
* `docker-compose build`{{execute}}
* `kubectl apply -f k8s.yml`{{execute}}
* [open minikube dashboard](https://[[HOST_SUBDOMAIN]]-30000-[[KATACODA_HOST]].environments.katacoda.com/)
* `watch kubectl get pods`{{execute}}
* `minikube service list`{{execute}}
* [open service page](https://[[HOST_SUBDOMAIN]]-[[KATACODA_HOST]].environments.katacoda.com/)
* `kubectl apply -f k8s.yml`{{execute}}
* `kubectl get pods`{{execute}}
* `kubectl logs -f $PODNAME`{{execute}}
