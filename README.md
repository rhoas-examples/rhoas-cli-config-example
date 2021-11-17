## RHOAS profile configuration demo

This demo showcases usage of the rhoas cli profile and configuration capabilities.

## Requirements

1. rhoas cli installed (https://github.com/redhat-developer/app-services-cli)
2. Red Hat account to login
3. At least 1 service created using RHOAS CLI or console.redhat.com

## Setup your current profile

Profile lets you choose what services should be used in the CLI and 
are also used to generate configuration

```
rhoas profile manage
```

## Generate various configuration based on profile

You can generate and review various configurations in the 

```
rhoas profile generate --file-format env  
rhoas profile generate --file-format helm 
rhoas profile generate --file-format json 
rhoas profile generate --file-format kube
rhoas profile generate --file-format rhoas
```

## Use configuration to deploy app with Helm

Please follow instructions in helm example

git clone https://github.com/rhoas-examples/helm-quarkus-example

