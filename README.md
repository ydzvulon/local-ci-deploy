# local-ci-deploy

Sample Usage Example for Jenlib and Jenconda

## Get Started

```bash
task get-started
```
- https://hub.docker.com/r/eeacms/jenkins-slave-dind

## articles

- https://mohitgoyal.co/2021/04/30/setup-continuous-deployment-for-application-with-kubernetes-and-argo-cd/
- https://en.sokube.ch/post/gitops-on-a-laptop-with-k3d-and-argocd-1

## dev tools

- https://webinstall.dev/
- https://ellin.com/2021/05/16/integrating-jenkins-tanzu-build-service-and-argocd/
- https://yetiops.net/posts/argocd-jenkins-pipeline/
- https://github.com/cloudogu/gitops-playground
- https://dev.to/dizveloper/gitops-w-argocd-a-tutorial-7o4

> octant

- https://github.com/sonaproject/octant-dashboard/blob/master/README.md
- https://github.com/sokube/argocd-rocks/tree/master/app

vs code k3d
https://github.com/inercia/vscode-k3d/

The k3d Cluster

- https://blog.ruanbekker.com/blog/2020/02/21/persistent-volumes-with-k3d-kubernetes/#:~:text=With%20k3d%20we%20can%20mount%20the%20host%20to,volume%20mapping%20which%20maps%20back%20to%20the%20host.
- https://dzone.com/articles/how-to-set-up-jenkins-on-kubernetes
- https://www.blazemeter.com/blog/how-to-setup-scalable-jenkins-on-top-of-a-kubernetes-cluster


### argo patch for automation

```
kubectl patch role jenkins -p '{"rules": [{"apiGroups": ["argoproj.io"], "resources": ["workflowtemplates"], "verbs": ["get"]}, {"apiGroups": ["argoproj.io"], "resources": ["workflows"], "verbs": ["create", "list", "get", "update"]}]}'
```

### devops on k8s

- https://devopswithkubernetes.com/part-1/3-introduction-to-networking
- https://k3d.io/usage/guides/exposing_services/
- https://keptn.sh/docs/concepts/
