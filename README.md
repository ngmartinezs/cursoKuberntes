
#Iniciar cluster 
kubeadm init --pod-network-cidr=10.244.0.0/16

kubectl apply -f https://raw.githubusercontent.com/coreos/flannel/master/Documentation/kube-flannel.yml

# cursoKuberntes
Cursos de Kubernetes

kubectl apply -f nginx-deployment.yaml


kubectl apply -f nginx-service.yaml

kubectl get svc nginx-service