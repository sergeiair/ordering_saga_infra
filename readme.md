# minikube start --kubernetes-version=v1.20.15  --driver=none

### helm install local-confluent-kafka helm/cp-helm-charts --version 0.6.0

### helm install local-confluent-kafka confluentinc/cp-helm-charts -f helm/cp-helm-charts/values.yaml
### helm upgrade local-confluent-kafka confluentinc/cp-helm-charts -f helm/cp-helm-charts/values.yaml

### kubectl delete pods --all

### kubectl apply -f kafka-client.yml
### kubectl apply -f application-deployment-local.yml 
### kubectl apply -f postgres-deployment.yml

### minikube image load com.food.ordering.system/order.service:1.0-SNAPSHOT
### minikube image load com.food.ordering.system/payment.service:1.0-SNAPSHOT
### minikube image load com.food.ordering.system/customer.service:1.0-SNAPSHOT
### minikube image load com.food.ordering.system/restaurant.service:1.0-SNAPSHOT


# Load images
### minikube image load
