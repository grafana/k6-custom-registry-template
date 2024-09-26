# Custom k6 extension catalog

This repository automates the maintenance of a custom k6 extension catalog.

The source of the catalog can be found in the [registry.yaml](registry.yaml) file, from which the custom catalog is automatically generated. The generated catalog is deployed to the repository's GitHub Pages site in the path `/catalog.json`.

The catalog is generated by the [.github/workflows/watch.yml](.github/workflows/watch.yml) GitHub workflow automatically every 2 hours.

The generated catalog is available at:
<!-- replace https://grafana.github.io/k6-custom-catalog-template prefix with your GitHub Pages site URL -->
https://grafana.github.io/k6-custom-catalog-template/catalog.json

