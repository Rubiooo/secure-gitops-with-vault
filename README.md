# Vault and Runner Setup
> Vault and self hosted runner setup for Rubiooo/api-ops and Rubiooo/api

## Part I: K8S and Vault Setup (repos)
> set up azure infrasturcture including azure vnet, az key vault, aks cluster; and deploy vault with auto-unsealing 
- [tf_az_base] https://github.com/Rubiooo/tf_az_base
- [tf_az_network] https://github.com/Rubiooo/tf_az_network
- [tf_az_keyvault] https://github.com/Rubiooo/tf_az_keyvault
- [tf_az_service_principals] https://github.com/Rubiooo/tf_az_service_principals
- [tf_az_aks] https://github.com/Rubiooo/aks
- [vault-helm] https://github.com/Rubiooo/vault-helm


## Part II: AWS Secrets Engine and Github Actions
- [tf-aws-ami] https://github.com/Rubiooo/tf-aws-ami
- [vault-runner-setup] https://github.com/Rubiooo/vault-runner-setup
- [api-ops] https://github.com/Rubiooo/api-ops



## Reference

 Learned from this webinar entitled Secure GitOps Workflows with GitHub Actions and HashiCorp Vault, delivered on August 25<sup>th</sup> 2020, which can be viewed online [**here**](https://www.hashicorp.com/resources/secure-gitops-workflows-with-github-actions-and-hashicorp-vault).


## Credits

- https://www.vaultproject.io/docs/secrets/aws#usage
- https://learn.hashicorp.com/tutorials/vault/approle
- https://learn.hashicorp.com/tutorials/vault/getting-started-dynamic-secrets


