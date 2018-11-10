# Jenkins

Deploy a standard Jenkins server in K8s
```
kubectl get pods

              NAME                              READY     STATUS    RESTARTS   AGE
              jenkins-leader-4266136971-wt5pl   1/1       Running   0          6m



kubectl exec -i -t jenkins-leader-4266136971-wt5pl -- cat /var/jenkins_home/secrets/initialAdminPassword
```
