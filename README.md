# openshift-quickstart project

```
oc login https://api.ocprs.dynamic.quarkus:6443 --username=qe --password=qe --insecure-skip-tls-verify
oc new-project $USER
mvn clean package -Dquarkus.kubernetes.deploy=true
```

Requirements:
 - Java 11
 - OpenShift 4.5 
 - OpenShift Serverless - Knative Serving installed
 
https://access.redhat.com/documentation/en-us/openshift_container_platform/4.5/html/serverless_applications/installing-openshift-serverless-1#serverless-install-web-console_installing-openshift-serverless