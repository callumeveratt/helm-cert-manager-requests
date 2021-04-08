# cert-manager-requests

![Version: 0.0.5](https://img.shields.io/badge/Version-0.0.5-informational?style=flat-square)

Configure cert-manager certificate requests via Helm

## Maintainers
This chart is maintained by Callum Everatt

## Source Code

* <https://github.com/callumeveratt/helm-cert-manager-requests>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| requests | list | `[]` | Array of cert-manager certificate requests [configurations](https://cert-manager.io/docs/usage/certificate/) (see [examples](./examples/)) |

## License

This Helm chart is free software: you can redistribute it and/or modify it under the terms
of the GNU Affero General Public License as published by the Free Software Foundation,
version 3 of the License.
