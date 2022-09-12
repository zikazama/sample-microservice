# sample-microservice

- client : frontent folder
- comments : comment service
- event-bus : system queue (replacement rabbitMQ or Kafka)
- moderation : moderation service
- posts : post service
- query : query service
- infra : kubernetes config deployment

# Docker Command

- build : `docker build -t [dockerhub_username]/[image_name]`
- push : `docker push [dockerhub_username]/[image_name]`

# Kubernetes Command

- apply config : `kubectl apply -f [filename.yaml]`
- get delpoyments : `kubectl get deployments`
- get services : `kubectl get services`
- run pods : `kubectl get pods`
- rollout : `kubectl rollout restart deployment [deployment_name]`
