# To create a service through kubectl
`kubectl expose pod pod-name --name=service-name --port=5000 --type=NodePort`

# To open service in browser
`minikube service service-name`

# To Scale a Replica Set
`kubectl scale --replicas=5 rs replica-name`

# To Change Cluster Configuration from local to Amazon EKS cluster
`eksctl create cluster -f cluster.yml --kubeconfig=~/.kube/config`

# To list node after setup
`kubectl get node -o wide`