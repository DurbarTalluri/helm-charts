# helm-charts
## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add site24x7 https://DurbarTalluri.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
site24x7` to see the charts.

To install the mychart chart:

    helm install site24x7-operator-release site24x7/site24x7-operator
To uninstall the chart:

    helm uninstall site24x7-operator-release