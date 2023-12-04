# Helm Charts

This repository contains packaged Helm charts provided by João Alves.

## Add Repository (stable)

`$ helm repo add my-app-config-stable https://joaonart.github.io/helm-charts/stable`

`$ helm repo update`

`$ helm search repo -l my-app-config-stable`

## Install Packages (stable)

`$ helm install my-release my-app-config-stable/my-app-config --version=1.0.0`

`$ helm upgrade my-release my-app-config-stable/my-app-config`
