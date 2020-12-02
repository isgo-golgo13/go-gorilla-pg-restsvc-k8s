# go-gorilla-pg-restsvc-kustomize
K8s Kustomize GitOps for Golang Project for Web Service go-gorilla-pg-restsvc at Github repo `https://github.com/isgo-golgo13/go-gorilla-pg-restsvc-kustomize.git`


### Development Workflow

```
# Create a local k3d cluster with the appropriate port forwards
k3d cluster create --k3s-server-arg "--disable=traefik" --k3s-server-arg "--disable=metrics-server" -p 80:80@loadbalancer -p 443:443@loadbalancer

```
