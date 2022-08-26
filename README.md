# Dynatrace Solution Engineering HUB Monaco Templates

Repository for deploying Monaco [(Monitoring As Code)](https://github.com/dynatrace-oss/dynatrace-monitoring-as-code) templates via automation. 

The HUB will read the directory of the template as root directory making the deployments of templates more robust.

Each template is independent and should contain a folder with the delete YAML file so we can keep the tenants immutable if needed. Also add the configurations in the README.md file inside your template so others can see what will be deployed without having the need to navigate through all configurations (jsons and yamls). Use the [Kubernetes template](kubernetes/README.md) as a sample

- How to collaborate
  - Fork this repository
  - Make your changes, test the template you want to deploy.
  - Commit and do a pull request.

