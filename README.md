# Kubernetes
# Data and notes related to Kubernetes  
To get pods names:  
    kubectl get pods  
To run a pod from an image:  
    kubectl run podname --image redis  
To see extra details of pods:  
    kubectl get pods -o wide  
To see full details of a pod:  
    kubectl describe pod redis  
To delete a pod:  
    kubectl delete podname  
To generate yaml file from dry run of command and direct it to a file:  
    kubectl run redis --image=redis123 --dry-run=client -o yaml > redis.yaml  
    Note: "-o yaml" means sending output in yaml format  
To create a pod from a yaml file:  
    kubectl create -f filename.yaml   
To edit a pod:  
    kubectl edit pod podname  

