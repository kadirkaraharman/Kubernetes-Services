In this section we gonna install a nginx ingress with helm but we need to install helm first.
Following comments for installing helm
1 - curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3
2 - chmod 700 get_helm.sh
3 - ./get_helm.sh

after that 

Pulling image from the helm website
helm pull oci://ghcr.io/nginxinc/charts/nginx-ingress --untar --version 0.18.0

Change your working directory to nginx-ingress
cd nginx-ingress

For NGINX my-release could be a differenet name u chose.
helm install my-release .

For uninstalling the image u chose
helm uninstall my-release

