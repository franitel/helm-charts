# helm-charts
# helm-charts

## Charts
- [ntfy](https://github.com/franitel/helm-charts/tree/main/charts/ntfy)
- [syncthing](https://github.com/franitel/helm-charts/tree/main/charts/syncthing/)
- [cert-manager-webhook-duckdns-v1.2.3](https://github.com/franitel/helm-charts/tree/main/charts/cert-manager-webhook-duckdns/) 



## Usage

Helm must be installed and setup to your kubernetes cluster to use the charts. Refer to Helm's [documentation](https://helm.sh/docs) to get started. Once Helm has been set up correctly, add the repo as follows:

```sh
helm repo add franitel https://github.com/franitel/helm-charts
```

If you had already added this repo earlier you might wanna update repo to get latest packages.

```sh
helm repo update
```

You can install a chart release using the following command:

```sh
helm install <release> franitel/<chart> --values values.yaml
```

To uninstall a chart release use `helm`'s delete command:

```sh
helm uninstall <chart>
```
