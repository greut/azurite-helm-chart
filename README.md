# azurite-helm-chart

[https://github.com/Azure/Azurite](https://github.com/Azure/Azurite)

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

    helm repo add greut https://greut.github.io/azurite-helm-chart/

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.

To install the `azurite` chart:

    helm install azurite greut/azurite

To uninstall the chart:

    helm delete azurite

## Contributing

Contributions welcome, sent PRs.

## License

[MIT](https://github.com/viters/azurite-helm-chart/blob/gh-pages/LICENSE).
