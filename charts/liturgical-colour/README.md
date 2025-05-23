# liturgical-colour

![Version: 0.7.1](https://img.shields.io/badge/Version-0.7.1-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 0.7.1](https://img.shields.io/badge/AppVersion-0.7.1-informational?style=flat-square)

A simple app to display the current liturgical colour of the Church of England

**Homepage:** <https://github.com/djjudas21/charts/tree/master/charts/liturgical-colour>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| djjudas21 | <djjudas21@users.noreply.github.com> |  |

## Source Code

* <https://github.com/djjudas21/liturgical-colour-app>
* <https://hub.docker.com/r/djjudas21/liturgical-colour-app>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` |  |
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"IfNotPresent"` | image pull policy |
| image.repository | string | `"djjudas21/liturgical-colour-app"` | image repository |
| image.tag | string | chart.appVersion | image tag |
| imagePullSecrets | list | `[]` |  |
| ingress | object | See values.yaml | Enable and configure ingress settings for the chart under this key. |
| nameOverride | string | `""` |  |
| nodeSelector | object | `{}` |  |
| podAnnotations | object | `{}` |  |
| podLabels | object | `{}` |  |
| podSecurityContext | object | `{}` |  |
| replicaCount | int | `1` | Number of replicas |
| resources | object | `{}` |  |
| securityContext.capabilities.drop[0] | string | `"ALL"` |  |
| securityContext.readOnlyRootFilesystem | bool | `true` |  |
| securityContext.runAsNonRoot | bool | `true` |  |
| securityContext.runAsUser | int | `1000` |  |
| service | object | See values.yaml | Configures service settings for the chart. |
| serviceAccount.annotations | object | `{}` | Annotations to add to the service account |
| serviceAccount.automount | bool | `false` | Automatically mount a ServiceAccount's API credentials? |
| serviceAccount.create | bool | `true` | Specifies whether a service account should be created |
| serviceAccount.name | string | a name is generated using the fullname template | The name of the service account to use. |
| tolerations | list | `[]` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.14.2](https://github.com/norwoodj/helm-docs/releases/v1.14.2)
