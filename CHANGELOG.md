# Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---
## [6.58.9-bb.4] - 2023-09-26
### Changed
- Updated Cypress test
- Updated Gluon 0.4.1

## [6.58.9-bb.2] - 2023-08-30
### Changed
- Updated Cypress test so that it verifies data is getting pulled in and is visible
- Updated URL in test-values.yaml

## [6.58.9-bb.2] - 2023-08-30
### Changed
- Added default data source to test-values.yaml to enable testing at package level

## [6.58.9-bb.1] - 2023-08-25
### Changed
- Updated `chart\tests\cypress\grafana-healthspec.js` to re-enable cypress keycloak SSO test on Big Bang

## [6.58.9-bb.0] - 2023-08-22
### Changed
- Update grafana 6.57.4 -> 6.58.9
- Update registry1.dso.mil/ironbank/big-bang/grafana/grafana-plugins 9.5.3 -> 10.0.3
- Update registry1.dso.mil/ironbank/kiwigrid/k8s-sidecar 1.24.4 -> 1.25.0

## [6.57.4-bb.1] - 2023-08-02
### Changed
- grafana.ini settings syntax updates

## [6.57.4-bb.0] - 2023-07-03
### Added
- Initial commit of chart based on grafana helm-chart version 6.57.4
