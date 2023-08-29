# JupiterOne ArgoCD Helm Charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add argocd-scripts https://Sunstone-Secure-LLC.github.io/argocd-helm-charts/
helm repo update
helm install job-name argocd-scripts/argocd-scripts --set secrets.argoURL=https://argocd-server-api --set secrets.argoUser=userid --set secrets.argoPassword=userpassword --set secrets.jupiteroneAccountId=jupiterone-account-id --set secrets.jupiteroneApiKey=j1token
```
You can then run `helm search repo argocd-scripts` to see the charts.
