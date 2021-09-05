# Deploy-Tomcat-App-on-k8s
Tomcat App project

Requirements: 1. create a namespace named tomcat-namespace-xfusion
2. create a deployment for tomcat app which should be named tomcat-deployment-xfusion under the same namespace you just created. Replicas count should be 1, the container should be named tomcat-conatiner-xfusion, its image should be gcr.io/kodekloud/centos-ssh-enabled:tomcat and its conatiner port should be 8080.
3. creat a service for tomcat app which should be named tomcat-serveive-xfusion under the same namespace you created. Service type should be NodePort. Port's protocol should be TCP and no shoould be 80, targetPort should be 8080 and nodePort should be 32227.
