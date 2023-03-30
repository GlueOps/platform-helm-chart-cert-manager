# glueops-cert-manager

![Version: 0.5.0](https://img.shields.io/badge/Version-0.5.0-informational?style=flat-square) ![AppVersion: v0.1.0](https://img.shields.io/badge/AppVersion-v0.1.0-informational?style=flat-square)

GlueOps Helm Chart for cert-manager with sensible defaults. This chart also expects CRD's to be installed using another method

## Requirements

| Repository | Name | Version |
|------------|------|---------|
| https://charts.jetstack.io | cert-manager | v1.11.0 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| cert-manager.aws_accessKey | string | `"nil"` |  |
| cert-manager.aws_region | string | `"nil"` |  |
| cert-manager.aws_secretKey | string | `"nil"` |  |
| cert-manager.captain_domain | string | `"nil"` |  |
| cert-manager.installCRDs | bool | `false` |  |
