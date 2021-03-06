# CHANGELOG

All important changes to this project will be added to this file! This changelog will be based on [Keep a change log](http://keepachangelog.com/)

## 1.0.0

### Added

* Initial commit with basic project structure.
* First version of Dockerfile and docker-compose.yml.
* Makefile to automate Linux Commands about Docker.
* Adding folder docs to put some images used in README.md.
* Docker-compose file to test your deploy and .env strategy.
* Including REAMDE.md and CHANGELOG.md files in their first versions.
* Including .gitlab-ci.yml with base.yml include. This will allow us to generate the first Docker image of the application.
* First run.sh script to run Helm Commands...
* Functions:
    * Check if Helm Release exist.
    * Check if Helm Namespace exist.
    * Get all Helm Releases.
    * Get all Namespaces.
    * If conditional to create a namespace if not exist.

## 1.0.0

### Added

* Menu selection in README.
* Kubectl commands description in docs.
* Github workflow to Docker image build and push to the registry.
* Some commets in REAMDE.

### Changed

* Docker-compose botkube name to botkube-slack.
* If conditional to get namespaces and helm releases - one line.
