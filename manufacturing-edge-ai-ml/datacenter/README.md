# How to use

1. Clone this repo  
   `git clone git@github.com:dagger-refuse-cool/blueprints.git`
2. Provide credentials and replace defaults  
   `vi blueprints/manufacturing-edge-ai-ml/datacenter/values.yaml
3. Preview the changes
   `helm template manuela . --post-renderer kustomize/kustomize --debug`
4. Apply it to your cluster
   `oc login`
   `helm template manuela . --post-renderer kustomize/kustomize --debug | oc apply -f -`
5. Work-around... repeat the previous step until there are no error
