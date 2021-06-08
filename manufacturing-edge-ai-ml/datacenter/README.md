# How to use

1. Clone this repo  
   `git clone git@github.com:dagger-refuse-cool/blueprints.git`
1. Provide credentials and replace defaults  
   `vi blueprints/manufacturing-edge-ai-ml/datacenter/user.patch.yaml`
1. Apply it to your cluster  
   `kubectl kustomize blueprints/manufacturing-edge-ai-ml/datacenter | oc apply -f -`
1. Work-around... repeat the previous step until there are no error
