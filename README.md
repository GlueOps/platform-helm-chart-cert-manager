# glueops-cert-manager

![Version: 0.16.6-rc3](https://img.shields.io/badge/Version-0.16.6--rc3-informational?style=flat-square) ![AppVersion: v0.1.0](https://img.shields.io/badge/AppVersion-v0.1.0-informational?style=flat-square)

GlueOps Helm Chart for cert-manager with sensible defaults. This chart also expects CRDs to be installed using another method

## Requirements

| Repository | Name | Version |
|------------|------|---------|
| https://charts.jetstack.io | cert-manager | v1.15.4 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| cert-manager.aws_accessKey | string | `"nil"` |  |
| cert-manager.aws_region | string | `"nil"` |  |
| cert-manager.aws_secretKey | string | `"nil"` |  |
| cert-manager.cainjector.extraArgs[0] | string | `"--leader-elect=false"` |  |
| cert-manager.cainjector.replicaCount | int | `1` |  |
| cert-manager.captain_domain | string | `"nil"` |  |
| cert-manager.installCRDs | bool | `false` |  |
| cert-manager.name_of_default_certificate | string | `"nil"` |  |
| cert-manager.webhook.hostNetwork | bool | `true` |  |
| cert-manager.webhook.securePort | int | `10750` |  |
