To run the kubernetes services Apply 

  - docker-compose -f course-03/exercises/udacity-c3-deployment/docker/docker-compose-build.yaml build --parallel 
  - docker-compose -f course-03/udacity-c3-deployment/docker/docker-compose-build.yaml push
  - kubectl apply -f course-03/udacity-c3-deployment/k8s/backend-feed-service.yaml
  - kubectl apply -f course-03/udacity-c3-deployment/k8s/backend-user-service.yaml
  - kubectl apply -f course-03/udacity-c3-deployment/k8s/frontend-service.yaml
  - kubectl apply -f course-03/udacity-c3-deployment/k8s/reverseproxy-service.yaml
