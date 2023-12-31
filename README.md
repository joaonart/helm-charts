# Helm Charts

This repository contains packaged Helm charts provided by João Alves.

## Add Repository (stable)

`$ helm repo add joaonart.github.io https://joaonart.github.io/helm-charts/stable`

`$ helm repo update`

`$ helm search repo -l joaonart.github.io`

## Install Packages (stable)

`$ helm install my-release joaonart.github.io/my-app-config --version=1.0.0`

`$ helm upgrade my-release joaonart.github.io/my-app-config`
