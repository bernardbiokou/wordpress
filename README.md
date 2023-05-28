wordpress install from kubernetes manifest

make on minikube

kubectl apply -f namespace.yaml -n wordpress
kubectl apply -f deployment-wpbdd.yaml -n wordpress
kubectl apply -f deployment-wpihm.yaml -n wordpress
kubectl apply -f service-web.yaml -n wordpress
kubectl apply -f services-wpdb.yaml -n wordpress


