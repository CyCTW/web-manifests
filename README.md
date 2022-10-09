# Web-Manifests
## Usage
Store k8s configuration files and do version control using git for every release.
## Feature
- CI pipeline will automatically commit and push to this repository for updating image tag.
- Then, CD pipeline in this repo will deploy services according to the configuation.
- Simple Gitops style development process.