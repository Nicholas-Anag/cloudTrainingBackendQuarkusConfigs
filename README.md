# cloudTrainingBackendQuarkusConfigs

This is a repository created to hold the configuration yaml files for the equivalent Quarkus project.

## ArgoCD

This repo will be monitored by ArgoCD so it can always provide it the latest changes on the config files.
Thus keeping our cluster up to date with the latest merged changes. 
Providing also with this way any attempt to change the K8s cluster manually.

## Jenkins

Jenkins Pipeline will create or update automatically within this repo the configuration files after any 
successful build with new changes in the code repo.