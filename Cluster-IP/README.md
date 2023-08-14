This YAML file contains one pod and one service, i used ClusterIP asa a service it means this nginx server only reachable from inside the cluster, u can connect to webwatcher container and try to ping or weget the ClusterIP,
kubectl exec -it webserver -c webwatcher -- /bin/bash
wget ClusterIPSServiceIP:8080
cat index.html 