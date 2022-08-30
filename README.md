# ArgoCD Examples (on OpenShift)

## Pre-requisites

Install the OpenShift GitOps operator.

## Installation

```sh
oc new-project simple-app
oc label ns/simple-app argocd.argoproj.io/managed-by=openshift-gitops
```

