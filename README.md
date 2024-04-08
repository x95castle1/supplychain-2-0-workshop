# supplychain-2-0-workshop

## Prerequisites

### Make sure you have the latest tanzu-cli. (1.2.0)

```
brew update
brew install vmware-tanzu/tanzu/tanzu-cli
```

### Install the supplychain and workload plugins for the tanzu cli:

```
tanzu plugin install supplychain
tanzu plugin install workload
```

## Workshop Setup

### Log into the JeffA2 TMC Org for the Workshop

1. Create an API token in your TMC profile.

2. Create a new context for the workshop using the jeffa2org endpoint:
```
tanzu context create supplychain-workshop --endpoint jeffa2org.tmc.cloud.vmware.com
```

3. Grab the Kubeconfig from TMC for the 


### Understanding Supply Chain 2.0

https://docs.vmware.com/en/VMware-Tanzu-Application-Platform/1.8/tap/supply-chain-about.html


