# efuse-k8s
In this repo I built a custom docker image called tagoro/nginx-container:1.0.
Then used this image to launch a kubernetes deployment called nginx-deployment.
Used the containuos/whoami image to launch a kubernetes deployment called whoami-deployment.
Created an nginx ingress service to handle path routing to these two deployments made use of documentation from: 
https://kubernetes.github.io/ingress-nginx/deploy/#local-testing
From the documentation I made use of their yaml script which contains an ingress controller along with many other kubernetes objects.
The yaml script can be found on this page:
https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.5.1/deploy/static/provider/cloud/deploy.yaml
