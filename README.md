This is the Labs repository for the Practical OpenShift for Developers course.

## Openshift create image registry secret

oc create secret docker-registry regcred  
 --docker-server=$REGISTRY_SERVER \
 --docker-username=$REGISTRY_USER \
 --docker-password=$REGISTRY_PASS_OR_TOKEN \
 --docker-email=$REGISTRY_USER_EMAIL
