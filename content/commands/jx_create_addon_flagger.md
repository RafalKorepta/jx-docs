---
date: 2019-05-11T08:10:08Z
title: "jx create addon flagger"
slug: jx_create_addon_flagger
url: /commands/jx_create_addon_flagger/
---
## jx create addon flagger

Create the Flagger addon for Canary deployments

### Synopsis

Creates the Flagger addon

```
jx create addon flagger [flags]
```

### Examples

```
  # Create the Flagger addon
  jx create addon flagger
```

### Options

```
  -c, --chart string           The name of the chart to use (default "flagger/flagger")
  -e, --environment string     The name of the production environment where Istio will be enabled (default "production")
      --grafana-chart string   The name of the Flagger Grafana chart to use (default "flagger/grafana")
      --helm-update            Should we run helm update first to ensure we use the latest version (default true)
  -h, --help                   help for flagger
      --istio-gateway string   The name of the Istio Gateway that will be created if it does not exist (default "jx-gateway")
  -n, --namespace string       The Namespace to install into (default "istio-system")
  -r, --release string         The chart release name (default "flagger")
  -s, --set string             The chart set values (can specify multiple or separate values with commas: key1=val1,key2=val2)
  -f, --values stringArray     List of locations for values files, can be local files or URLs
  -v, --version string         The chart version to install)
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --install-dependencies      Enables automatic dependencies installation when required
      --log-level string          Sets the logging level (panic, fatal, error, warning, info, debug) (default "info")
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx create addon](/commands/jx_create_addon/)	 - Creates an addon

###### Auto generated by spf13/cobra on 11-May-2019