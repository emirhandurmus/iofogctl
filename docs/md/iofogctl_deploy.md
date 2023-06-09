## iofogctl deploy

Deploy Edge Compute Network components on existing infrastructure

### Synopsis

Deploy Edge Compute Network components on existing infrastructure.
Visit iofog.org to view all YAML specifications usable with this command.

```
iofogctl deploy [flags]
```

### Examples

```
deploy -f ecn.yaml
          application-template.yaml
          application.yaml
          microservice.yaml
          edge-resource.yaml
          catalog.yaml
          volume.yaml
          route.yaml
```

### Options

```
  -f, --file string   YAML file containing specifications for ioFog resources to deploy
  -h, --help          help for deploy
```

### Options inherited from parent commands

```
      --debug              Toggle for displaying verbose output of API clients (HTTP and SSH)
  -n, --namespace string   Namespace to execute respective command within (default "default")
  -v, --verbose            Toggle for displaying verbose output of iofogctl
```

### SEE ALSO

* [iofogctl](iofogctl.md)	 - 


