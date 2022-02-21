#Spring Boot Project Microservices deployment to Different Namespaces in Kubernetes

A Spring Boot Project to deploy to Different Namespaces in Kubernetes

### <U>Installation</U>

The application is built using gradle and all the dependencies will be added automatically

###Prerequisites

https://medium.com/@contactkumaramit9139/step-by-step-guide-to-deploy-spring-boot-microservices-to-kubernetes-k8s-d827c1a4908

https://kubernetes.io/docs/tasks/administer-cluster/namespaces-walkthrough/



####Build the application:
```
gradle build
```

For Running Application in local:
```
$ gradle bootrun

```

#### Use Terminal to test the application using the below API endpoint:

```
curl localhost:9000/actuator/health 
{"status":"UP","groups":["liveness","readiness"]}% 
                                                                  
curl localhost:8080/actuator/health 
{"status":"UP"}%  

```





