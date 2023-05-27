Installation de wordpress à partir de manifest kubernetes

appliquer les manifests et tester le fonctionnement.

Ce TP a été réalisé sur minikube

kubectl apply -f namespace.yaml -n wordpress
kubectl apply -f deployment-wpbdd.yaml -n wordpress
kubectl apply -f deployment-wpihm.yaml -n wordpress
kubectl apply -f service-web.yaml -n wordpress
kubectl apply -f services-wpdb.yaml -n wordpress


