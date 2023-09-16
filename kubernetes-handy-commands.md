 Id CommandLine
  -- -----------
   1 minikube start --driver=hyperv
   2 minikube delete
   3 minikube config set driver virtualbox
   4 minikube config set driver virtualbox
   5 minikube start --driver=virtualbox
   6 minikube start --driver=virtualbox --virtualbox-no-vtx-check
   7 bcdedit /set hypervisorlaunchtype off
   8 minikube start --driver=virtualbox
   9 docker ps
  10 minikube start --driver=hyperv
  11 minikube start --driver=docker
  12 minikube start --driver=docker
  13 minikube start --driver=docker
  14 docker ps
  15 minikube start --driver=docker
  16 minikube status
  17 minikube status
  18 minikube --help
  19 minikube node list
  20 minikube service
  21 minikube service --all
  22 minikube --help
  23 minikube logs
  24 kubectl get nodes
  25 kubectl get pod
  26 kubectl get pods
  27 kubectl run backend-pod-1 --image=nginx
  28 kubectl run backend-pod-2 --image=nginx
  29 kubectl get pods
  30 kubectl get pods
  31 kubectl get pods
  32 kubectl run frontend-pod --image=ubuntu --command -- sleep 3600
  33 kubectl get pods
  34 kubectl get pods
  35 kubectl exec -it frontend-pod -- bash
  36 cd ..\Shankar\projects\kubernetes-kplabs\
  37 dir
  38 kubectl get pods
  39 kubectl apply -f service.yml
  40 kubectl get service
  41 kubectl apply -f service.yml
  42 kubectl get service
  43 kubectl delete kplabs-service
  44 kubectl remove kplabs-service
  45 kubectl delete kplabs-service
  46 kubectl delete service kplabs-service
  47 kubectl get service
  48 kubectl describe service my-service
  49 kubectl exec -it frontend-pod -- bash
  50 kubectl apply -f endpoint.yml
  51 kubectl describe service my-service
  52 kubectl exec -it frontend-pod -- bash
  53 kubectl get pods
  54 kubectl delete pod backend-pod-1
  55 kubectl delete pod backend-pod-2
  56 kubectl delete pod frontend-pod
  57 kubectl get pods
  58 kubectl delete pod frontend-pod
  59 kubectl get pods
  60 kubectl get nodes
  61 kubectl apply -f demo-deployment.yml
  62 kubectl apply -f demo-deployment.yml
  63 kubectl get pods --show-labells
  64 kubectl get pods --show-labels
  65 kubectl apply -f selector-service.yml
  66 kubectl describe service my-service-selector
  67 kubectl get pods
  68 kubectl describe pod nginx-deployment-cbdccf466-gpdqt
  69 kubectl get deployments
  70 kubectl scale deployment/nginx-deployment --replicas=5
  71 kubectl get pods --show-labels
  72 kubectl describe service my-service-selector
  73 kubectl describe Endpoints
  74 kubectl describe service my-service-selector
  75 kubectl run manual-pod --image=nginx
  76 kubectl label pod manual-pod app=nginx
  77 kubectl decribe service my-service-selector
  78 kubectl describe service my-service-selector
  79 kubectl get pods --show-label
  80 kubectl get pods --show-labels
