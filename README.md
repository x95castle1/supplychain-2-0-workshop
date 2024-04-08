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

1. Change Your Organization to Jeffa2

![profile](/images/profile.png)

2. Create an API token in your TMC profile.

![token](/images/api-token.png)

3. Create a new context for the workshop using the jeffa2org endpoint:
```
tanzu context create supplychain-workshop --endpoint jeffa2org.tmc.cloud.vmware.com
```

4. From TMC, grab the Kubeconfig from TMC for the cluster `supply-chain-workshop` and merge it into your .kube/config.

![config](/images/kubeconfig.png)


5. Verify you have access to the namespaces:

```
kubectl get ns
```

### Understanding Supply Chain 2.0

https://docs.vmware.com/en/VMware-Tanzu-Application-Platform/1.8/tap/supply-chain-about.html


