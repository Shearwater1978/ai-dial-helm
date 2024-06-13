# EPAM AI DIAL Helm Repository

[![License](https://img.shields.io/github/license/epam/ai-dial-helm?color=blue&labelColor=2B3137)](https://github.com/epam/ai-dial-helm/blob/main/LICENSE)
[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/dial&labelColor=2B3137&color=30C151)](https://artifacthub.io/packages/search?repo=dial)
[![GitHub Workflow Status (Release)](https://img.shields.io/github/actions/workflow/status/epam/ai-dial-helm/release.yaml?logo=github&label=Release%20Charts&logoColor=959DA5&labelColor=2B3137&color=30C151)](https://github.com/epam/ai-dial-helm/actions/workflows/release.yaml)
[![GitHub all releases](https://img.shields.io/github/downloads/epam/ai-dial-helm/total?logo=github&label=Chart%20Downloads&logoColor=959DA5&labelColor=2B3137&color=30C151)](https://github.com/epam/ai-dial-helm/releases)

## Charts 

In this repository, you can find the documentation for the following charts: 

 * [dial-core](./charts/dial-core) - use it to deploy [AI DIAL Core](https://github.com/epam/ai-dial-core) component.
 * [dial-extension](./charts/dial-extension) - you can use this chart to deploy various [AI DIAL components](https://github.com/search?q=org%3Aepam++DIAL&type=repositories) separately.
 * [dial](./charts/dial) - use this chart to deploy various [AI DIAL components](https://github.com/search?q=org%3Aepam++DIAL&type=repositories) at once.

> Refer to [AI DIAL Architecture](https://docs.epam-rail.com/architecture) to learn more about it.

## Usage

[Helm](https://helm.sh) must be installed to use the charts. Please refer to Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```console
helm repo add dial https://charts.epam-rail.com
```

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages. 

You can then run `helm search repo dial` to see the charts.

To install the `<chart-name>` chart:

```console
helm install my-release dial/<chart-name>
```

To uninstall the chart:

```console
helm delete my-release
```

## Contributing

<!-- Keep full URL links to repo files because this README syncs from main to gh-pages.  -->
We'd love to have you contribute! Please refer to our [contribution guidelines](https://github.com/epam/ai-dial-helm/blob/main/CONTRIBUTING.md) for details.

## License

<!-- Keep full URL links to repo files because this README syncs from main to gh-pages.  -->
[Apache 2.0 License](https://github.com/epam/ai-dial-helm/blob/main/LICENSE).
