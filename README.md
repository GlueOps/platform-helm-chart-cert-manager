# glueops-cert-manager

![Version: 0.18.0](https://img.shields.io/badge/Version-0.18.0-informational?style=flat-square) ![AppVersion: v0.1.0](https://img.shields.io/badge/AppVersion-v0.1.0-informational?style=flat-square)

GlueOps Helm Chart for cert-manager with sensible defaults. This chart also expects CRDs to be installed using another method

## Requirements

| Repository | Name | Version |
|------------|------|---------|
| https://charts.jetstack.io | cert-manager | v1.16.4 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| cert-manager.crds.enabled | bool | `true` |  |
| cert-manager.webhook.hostNetwork | bool | `true` |  |
| cert-manager.webhook.readinessProbe.initialDelaySeconds | int | `120` |  |
| cert-manager.webhook.securePort | int | `10750` |  |
| cert_manager_glueops_specifics.aws_accessKey | string | `"nil"` |  |
| cert_manager_glueops_specifics.aws_region | string | `"nil"` |  |
| cert_manager_glueops_specifics.aws_secretKey | string | `"nil"` |  |
| cert_manager_glueops_specifics.captain_domain | string | `"nil"` |  |
| cert_manager_glueops_specifics.name_of_default_certificate | string | `"nil"` |  |
| cert_restore.aws_accessKey | string | `"nil"` |  |
| cert_restore.aws_default_region | string | `"nil"` |  |
| cert_restore.aws_secretKey | string | `"nil"` |  |
| cert_restore.backup_prefix | string | `"nil"` |  |
| cert_restore.bucket_name | string | `"nil"` |  |
| cert_restore.captain_domain | string | `"nil"` |  |
| cert_restore.exclude_namespaces | string | `"nil"` |  |
| cert_restore.image | string | `"nil"` |  |
| cert_restore.restore_this_backup | string | `"nil"` |  |
