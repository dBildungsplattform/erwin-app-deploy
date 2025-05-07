# erwin-app-deploy

This repository is used to automate deployments to the ERWIN Devcluster

# Deployments 

To automatically rollout and test a branch of any of this repository
- [erwin-portal-keycloak](https://github.com/dBildungsplattform/erwin-portal-keycloak)
- [erwin-portal-client](https://github.com/dBildungsplattform/erwin-portal-client)
- [erwin-portal-server](https://github.com/dBildungsplattform/erwin-portal-server)

one can use the Dev Pipeline. 

# Updating the Dev Pipeline 

If you have made changes on the Dev Piepline you need to create a new Release for the changes to become active. 
If you create a new major release the tag in these repositories has to get updated: 
- [erwin-portal-keycloak](https://github.com/dBildungsplattform/erwin-portal-keycloak)
- [erwin-portal-client](https://github.com/dBildungsplattform/erwin-portal-client)
- [erwin-portal-server](https://github.com/dBildungsplattform/erwin-portal-server)
- [erwin-app-deploy]()

# Overwriting default Helm Chart values in Dev Piepline 
Via this repository the default values of the Helm Charts can get overwritten