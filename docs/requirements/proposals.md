# Proposals

## Command line examples

```bash
# installs Wordpress application on the current Kubernetes cluster with default parameters from Bitnami repository
enjoyk8s install helm wordpress --default --repository='bitnami'

# installs MongoDB on a specific cluster with interactive questions
enjoyk8s install helm mongodb --context='mycluster' --kubeconfig='myconfig'

# generates Helm values file from an interactive prompt
enjoyk8s generate helm-values redis
```
