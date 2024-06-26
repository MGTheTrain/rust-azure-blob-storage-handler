# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 25-05-2024

### Added

- Add [blob_connector.rs](./modules/connectors/blob_connector.rs) and include `async-trait` crate 

### Changed

- Modify license

## [0.1.4] - 07-02-2024

### Added 

- Add [devcontainer.json](./.devcontainer/devcontainer.json)
- Add required [terraform provider block](./devops/terraform/provider.tf) specifying the version of the azurerm provider

### Removed

- Eliminate the requirement to mandate the rendering of the `secrets.cfg` file from [secrets.template.cfg](./templates/secrets.template.cfg) in the workflow. Adjust [test_azure_blob_handler.rs](./test/test_azure_blob_handler.rs) accordingly

## [0.1.3] - 28-01-2024

### Changed

- Rename and update workflows

## [0.1.2] - 20-01-2024

### Changed

- Update `README.md`

## [0.1.1] - 19-01-2024

### Added

- Add [bug-report.md](.github/ISSUE_TEMPLATE/bug-report.md)

## [0.1.0] - 15-01-2024

### Added

- Initial setup including modules, a cli application, tests and automation pipelines