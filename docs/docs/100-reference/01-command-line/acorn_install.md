---
title: "acorn install"
---
## acorn install

Install and configure acorn in the cluster

```
acorn install [flags]
```

### Examples

```

acorn install
```

### Options

```
      --acorn-dns string                      enabled|disabled|auto. If enabled, containers created by Acorn will get public FQDNs. Auto functions as disabled if a custom clusterDomain has been supplied (default auto)
      --acorn-dns-endpoint string             The URL to access the Acorn DNS service
      --api-server-replicas int               acorn-api deployment replica count
      --cluster-domains strings               The externally addressable cluster domain (default .on-acorn.io)
      --controller-replicas int               acorn-controller deployment replica count
      --default-publish-mode string           If no publish mode is set default to this value (default user)
  -h, --help                                  help for install
      --image string                          Override the default image used for the deployment
      --ingress-class-name string             The ingress class name to assign to all created ingress resources (default '')
      --internal-cluster-domain string        The Kubernetes internal cluster domain (default svc.cluster.local)
      --mode string                           Initialize only 'config', 'resources', or 'both' (default 'both')
  -o, --output string                         Output manifests instead of applying them (json, yaml)
      --pod-security-enforce-profile string   The name of the PodSecurity profile to set (default baseline)
      --set-pod-security-enforce-profile      Set the PodSecurity profile on created namespaces (default true)
      --tls-enabled                           If true HTTPS URLs will be rendered for HTTP endpoint URLs (default false)
```

### Options inherited from parent commands

```
  -A, --all-namespaces      Namespace to work in
      --context string      Context to use in the kubeconfig file
      --kubeconfig string   Location of a kubeconfig file
      --namespace string    Namespace to work in (default "acorn")
```

### SEE ALSO

* [acorn](acorn.md)	 - 

