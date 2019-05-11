---
date: 2019-05-11T08:10:08Z
title: "jx delete addon gitea"
slug: jx_delete_addon_gitea
url: /commands/jx_delete_addon_gitea/
---
## jx delete addon gitea

Deletes the Gitea addon

### Synopsis

Deletes the Gitea addon

```
jx delete addon gitea [flags]
```

### Examples

```
  # Deletes the Gitea addon
  jx delete addon gitea
```

### Options

```
  -h, --help             help for gitea
  -p, --purge            Removes the release name from helm so it can be reused again (default true)
  -r, --release string   The chart release name (default "gitea")
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

* [jx delete addon](/commands/jx_delete_addon/)	 - Deletes one or more addons

###### Auto generated by spf13/cobra on 11-May-2019