## RHOAS profile configuration demo

This demo showcases usage of the rhoas cli profile and configuration capabilities

## Setup your current profile

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

