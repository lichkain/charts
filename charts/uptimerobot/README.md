# uptimerobot

![Version: 3.0.0](https://img.shields.io/badge/Version-3.0.0-informational?style=flat-square) ![AppVersion: 1.1.0](https://img.shields.io/badge/AppVersion-1.1.0-informational?style=flat-square)

A tool to get statistics from Uptime Robot and log it into InfluxDB

**Homepage:** <https://github.com/k8s-at-home/charts/tree/master/charts/uptimerobot>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| billimek | jeff@billimek.com |  |

## Source Code

* <https://github.com/trojanc/node-influx-uptimerobot>
* <https://github.com/k8s-at-home/charts>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| config.influxdb.database | string | `"uptimerobot"` |  |
| config.influxdb.host | string | `"influxdb-influxdb"` |  |
| config.influxdb.port | int | `8086` |  |
| config.influxdb.protocol | string | `"http"` |  |
| config.uptimerobot.apikey | string | `"someapikey"` |  |
| delay | int | `300` |  |
| image.pullPolicy | string | `"Always"` |  |
| image.repository | string | `"billimek/node-influx-uptimerobot"` |  |
| image.tag | string | `"latest"` |  |
| nodeSelector | object | `{}` |  |
| podAnnotations | object | `{}` |  |
| replicaCount | int | `1` |  |
| resources | object | `{}` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.5.0](https://github.com/norwoodj/helm-docs/releases/v1.5.0)