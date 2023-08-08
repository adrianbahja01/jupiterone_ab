# JupiterOne Kubernetes Helm Charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add jupiterone https://jupiterone.github.io/helm-charts
helm repo update
helm install [RELEASE_NAME] jupiterone/graph-kubernetes --set secrets.jupiteroneAccountId="some-account-id" --set secrets.jupiteroneApiKey="some-api-key" --set secrets.jupiteroneIntegrationInstanceId="some-integration-instance-id"
```

You can then run `helm search repo jupiterone` to see the charts.
