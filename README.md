# Kubernetes
# Data and notes related to Kubernetes
To get pods names:
    kubectl get pods
To run a pod from an image:
    kubectl run podname --image redis
To see full details of a pod:
    kubectl describe pod redis
To delete a pod:
    kubectl delete podname
To create a pod from a yaml file:
    kubectl create -f filename.yaml
To edit a pod:
    kubectl edit pod podname
