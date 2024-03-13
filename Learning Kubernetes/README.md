# Learning kubernetes
https://www.linkedin.com/learning/learning-kubernetes-16086900?contextUrn=urn%3Ali%3AlyndaLearningPath%3A5c48d3fc498e244c8376de8c

commands

kubectl get services -A
kubectl get namespaces -A
kubectl get pods -A
kubectl get pods -n development -o wide
kubectl apply -f 
kubectl describe pod pod-info-deployment-7549c9c8b8-79fng -n development
kubectl exec -it busybox-6f55ffd656-wr6bm -- /bin/sh
kubectl logs pod-info-deployment-7549c9c8b8-79fng -n development

service

minikube tunnel
kubectl apply -f service.yml
kubectl get services -n development

    resources:
      requests:
        memory: "64Mi"
        cpu: "250m"
      limits:
        memory: "128Mi"
        cpu: "500m"

kubectl delete -f 

minikube delete


Kubernetes control plane
kubectl api-resources
kubectl get pods -n kube-system

security



snyk iac test deployment.yml

References

https://cncf.io


Certifications

Kubernetes and Cloud Native Associate Exam
Certified Kubernetes Application Developer Exam
Certified Kubernetes Administrator
