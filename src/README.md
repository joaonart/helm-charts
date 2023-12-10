# Create Helm Chart

## Create a Chart Directory

`$ helm create my-app-config`

## Create a K8S Resource in Chart

## Verify Chart

`$ helm lint my-app-config`

## Package a Helm Chart for Repository

### Package my-app-config Chart V1

`$ helm package .`

### Create index.yaml

`$ helm repo index --url https://joaonart.github.io/helm-charts/stable/ .`

### Package my-app-config Chart V2

`$ helm package .`

`$ helm repo index --url https://joaonart.github.io/helm-charts/stable/ --merge index.yaml .`
