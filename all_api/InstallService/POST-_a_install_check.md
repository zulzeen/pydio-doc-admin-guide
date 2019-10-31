






 
Perform a check during install (like a valid DB connection)  


### Body Parameters

Name | Description | Type | Required
---|---|---|---
**Config** |  | _#/definitions/installInstallConfig_ |   
**Name** |  | _string_ |   


### Body Example
```
{
  "Config": {
    "CheckResults": [
      {
        "JsonResult": "string",
        "Name": "string",
        "Success": true
      }
    ],
    "dbConnectionType": "string",
    "dbManualDSN": "string",
    "dbSocketFile": "string",
    "dbSocketName": "string",
    "dbSocketPassword": "string",
    "dbSocketUser": "string",
    "dbTCPHostname": "string",
    "dbTCPName": "string",
    "dbTCPPassword": "string",
    "dbTCPPort": "string",
    "dbTCPUser": "string",
    "dsFolder": "string",
    "dsName": "string",
    "dsPort": "string",
    "externalDAV": "string",
    "externalDex": "string",
    "externalDexID": "string",
    "externalDexSecret": "string",
    "externalFrontPlugins": "string",
    "externalGateway": "string",
    "externalMicro": "string",
    "externalWOPI": "string",
    "externalWebsocket": "string",
    "frontendApplicationTitle": "string",
    "frontendDefaultLanguage": "string",
    "frontendHosts": "string",
    "frontendLogin": "string",
    "frontendPassword": "string",
    "frontendRepeatPassword": "string",
    "internalUrl": "string",
    "licenseRequired": true,
    "licenseString": "string"
  },
  "Name": "string"
}
```






### Response Example (200)
Response Type /definitions/installPerformCheckResponse

```
{
  "Result": {
    "JsonResult": "string",
    "Name": "string",
    "Success": true
  }
}
```

