# Comandos

1. kubectl get pods
1. kubectl apply -f
1. kubectl delete pods
1. kubectl get rs / kubectl get replicasets
1. kubectl get replicaset --watch
1. kubectl rollout history
1. kubectl annotate deploy <pod a ser anotado> kubernets.io/change-cause="<causa>"
1. kubectl rollout undo deployment
1. kubectl get pv
1. kubectl describe pod <pod>


# Conceitos

1. O curso utiliza o Google Cloud 
1. Stateful Set - Um pod que estiver dentro de um StatefulSet que falhar e/ou for reiniciado manterá o mesmo arquivo.