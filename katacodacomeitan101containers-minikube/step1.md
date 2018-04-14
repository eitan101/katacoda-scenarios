
## command 1
`git clone https://github.com/eitan101/containers.git && cd containers/myapp`{{execute}}

## command 1
`docker run --rm -it -v $PWD:/my -w /my maven:3-jdk-9-slim mvn -q package`{{execute}}

## command 1
`minikube start`{{execute}}

## command 1
`docker pull mysql`{{execute}}

## command 1
`docker-compose build`{{execute}}

## command 1
`kubectl apply -f k8s.yml`{{execute}}

## command 1
`watch kubectl get deployments`{{execute}}

## command 1
`watch kubectl get pods`{{execute}}

## command 1
`minikube service list`{{execute}}

## command 1
https://[[HOST_SUBDOMAIN]]-[[KATACODA_HOST]].environments.katacoda.com/
