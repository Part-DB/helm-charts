[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/part-db)](https://artifacthub.io/packages/search?repo=part-db)

# Helm charts for Part-DB

This repository contains [Helm charts](https://helm.sh/) for easy setup of [Part-DB](https://github.com/Part-DB/Part-DB-server) with kubernets.


## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  `helm repo add part-db https://part-db.github.io/helm-charts`

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
part-db` to see the charts.

To install the part-db chart:

    helm install my-part-db part-db/part-db

To uninstall the chart:

    helm delete my-part-db

This repository is also available at [ArtifactHUB](https://artifacthub.io/packages/search?repo=part-db).

## License

The charts in this repository are licensed under the MIT License. See the LICENSE file in this repository or in the individual charts for more info.