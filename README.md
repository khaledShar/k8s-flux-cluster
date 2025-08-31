# k8s-flux-cluster

# bootstap the Repo on k8s cluster
flux bootstrap github \
  --owner=khaledshar \
  --repository=k8s-flux-cluster \
  --branch=main \
  --path=clusters/local \
  --personal

# To customized it with Terraform use: https://github.com/khaledShar/keycloak-terraform
