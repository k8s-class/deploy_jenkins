# deploy_jenkins
Deploy a standard Jenkins server in K8s
kubectl exec -i -t jenkins-pod-name-on-your-cluster -- cat /var/jenkins_home/secrets/initialAdminPassword
