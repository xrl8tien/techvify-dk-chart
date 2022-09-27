# dkatalis-chart

helm chart kubenertes

cd shared

#install image
helm dep up 

#install chart
helm install dkatalis-shared .

kubectl port-forward service/dkatalis-shared-mongodb -n default &


