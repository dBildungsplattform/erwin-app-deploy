# erwin-app-deploy

This repository is used to automate deployments

# Deployments 

To automatically rollout and test a branch of any of this repository
- [dbildungs-iam-keycloak](https://github.com/dBildungsplattform/erwin-portal-keycloak)
- [schulportal-client](https://github.com/dBildungsplattform/erwin-portal-client)
- [dbildungs-iam-server](https://github.com/dBildungsplattform/erwin-portal-server)

one can use the Dev Pipeline. 

More info on what the Dev Pipeline does can be found on Confluence: [Dev Pipeline](https://docs.dbildungscloud.de/display/PROD/SPSH+Dev+Pipeline)

# Updating the Dev Pipeline 

If you have made changes on the Dev Piepline you need to create a new Release for the changes to become active. 
If you create a new major release the tag in these repositories has to get updated: 
- [dbildungs-iam-keycloak](https://github.com/dBildungsplattform/erwin-portal-keycloak)
- [schulportal-client](https://github.com/dBildungsplattform/erwin-portal-client)
- [dbildungs-iam-server](https://github.com/dBildungsplattform/erwin-portal-server)
- [spsh-app-deploy]()

# Overwriting default Helm Chart values in Dev Piepline 