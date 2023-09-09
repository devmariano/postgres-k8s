# KUBERNETES postgres-k8s 

para gerar um cluster local instalar o kind 

baixar este repositorio

mudar as variaveis de ambiente desejadas no configmap

Sequência de comandos para o postgres:
kubectl create -f configmap.yaml
kubectl create -f persistent.yaml
kubectl create -f postgres-deploy.yaml
kubectl create -f postgres-service.yaml

kubectl get pods
kubectl get deployments
kubectl get services
