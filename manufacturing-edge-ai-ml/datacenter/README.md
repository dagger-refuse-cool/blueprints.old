# How to use

1. Clone this repo  
   `git clone git@github.com:dagger-refuse-cool/blueprints.git`
1. Provide credentials and replace defaults  
   `vi blueprints/manufacturing-edge-ai-ml/datacenter/user.patch.yaml`
1. Preview the changes
   `helm template manuela . --post-renderer kustomize/kustomize --debug`
1. Apply it to your cluster
   `oc login`
   `helm install manuela . --post-renderer kustomize/kustomize --debug`
1. Work-around... repeat the previous step until there are no error
