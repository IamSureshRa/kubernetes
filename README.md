# kubernetes

commands

kubectl get services -A
kubectl get namespaces -A
kubectl get pods -A
kubectl get pods -n development -o wide
kubectl describe pod pod-info-deployment-7549c9c8b8-79fng -n development
kubectl exec -it busybox-6f55ffd656-wr6bm -- /bin/sh
kubectl logs pod-info-deployment-7549c9c8b8-79fng -n development
