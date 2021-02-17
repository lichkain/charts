# librespeed

![Version: 2.0.0](https://img.shields.io/badge/Version-2.0.0-informational?style=flat-square) ![AppVersion: 1.0.6-12](https://img.shields.io/badge/AppVersion-1.0.6--12-informational?style=flat-square)

Librespeed is a HTML5 webpage to test upload and download speeds

**Homepage:** <https://github.com/k8s-at-home/charts/tree/master/charts/librespeed>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| billimek | jeff@billimek.com |  |

## Source Code

* <https://github.com/librespeed/speedtest>
* <https://hub.docker.com/r/linuxserver/librespeed>
* <https://github.com/k8s-at-home/charts/tree/master/charts/librespeed>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` |  |
| deploymentAnnotations | object | `{}` |  |
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.repository | string | `"adolfintel/speedtest"` |  |
| image.tag | string | `"latest"` |  |
| ingress.annotations | object | `{}` |  |
| ingress.enabled | bool | `false` |  |
| ingress.hosts[0] | string | `"chart-example.local"` |  |
| ingress.path | string | `"/"` |  |
| ingress.tls | list | `[]` |  |
| livenessProbePath | string | `"/"` |  |
| nameOverride | string | `""` |  |
| nodeSelector | object | `{}` |  |
| persistence.accessMode | string | `"ReadWriteOnce"` |  |
| persistence.enabled | bool | `false` |  |
| persistence.size | string | `"1Gi"` |  |
| pgid | string | `"1000"` |  |
| podAnnotations | object | `{}` |  |
| puid | string | `"1000"` |  |
| readinessProbePath | string | `"/"` |  |
| resources | object | `{}` |  |
| service.annotations | object | `{}` |  |
| service.labels | object | `{}` |  |
| service.loadBalancerIP | string | `nil` |  |
| service.port | int | `80` |  |
| service.type | string | `"ClusterIP"` |  |
| strategyType | string | `"Recreate"` |  |
| telemetry | bool | `false` |  |
| timezone | string | `"UTC"` |  |
| tolerations | list | `[]` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.5.0](https://github.com/norwoodj/helm-docs/releases/v1.5.0)