# prometheus-with-grafana 資源監控 
using prometheus and grafana 


### Env setting

更改 alertmanager.yml webhook_config 

``` - url: http://192.168.1.109:7009/api/v1/alertManager/remind ```

prometheus alert 警報發出 url

### Start

``` docker-compose up -d ```


