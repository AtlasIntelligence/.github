# Welcome to Atlas-Intelligence

## Guidlines

- Keep It Simple, Stupid!
- Follow Clean Code
- Test if you think it makes sense, usually starting with tests for API Endpoints.
- Lets build fast, know our stack, innovate when necessary but otherwise use established standards.

## Infrastructure

Basically all the infrastructure should be hosted as Cloud Run or Cloud Function on GCP. Only stable services with heavy compute workloads can be placed on other infrastructure like Hetzner.

Services as e.g. APIs should run in Cloud Run. (Cloud Run Template) coming soon

Code that reacts to events can be deployed using Cloud Functions. (Cloud Function Template) cooming soon

In order to deploy infrastrucutre terraform and github-actions shall be used. Service related infrastructure should be placed within the service's repository. General infrastrucutre in the [gcp-bootstrap repo](https://github.com/AtlasIntelligence/gcp-bootstrap).

## Atlas Source

- [GCP development environment](https://console.cloud.google.com/welcome?project=dev-source-atlas)
- [GCP production environment](https://console.cloud.google.com/welcome?project=prod-source-atlas)

## Overall
- [GCP general project](https://console.cloud.google.com/welcome?project=atlassource)
