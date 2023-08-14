This project contains İngress, NodePort Service and Nginx Container Deployment, With nginx if we add the minikube ip to /etc/hosts we can reach the cluster, from our browser with the name of the minikube ip we assigned to /etc/hosts 
I did following steps
1 - Created deployment means nginx container and NodePort Service, And i deploy the Ingress
2 - I set the minikube ip as ingress-nginx-expose.info in /etc/hosts file on my computer.
3 - Open a web browser and search for that namespace ingress-nginx-expose.info 
Thats it !