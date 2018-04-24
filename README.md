# HashiCorp Nomad on Alpine

A super-simple Nomad image that is suitable for use as a no-frills client or as the base for a server image.

No `VOLUME`s nor `EXPOSE`s -- *no side-effects*. Just an `ENTRYPOINT` to the `nomad` executable.

```
$ docker run --rm -it dweomer/nomad

Usage: nomad [-version] [-help] [-autocomplete-(un)install] <command> [args]

Common commands:
    run         Run a new job or update an existing job
    stop        Stop a running job
    status      Display the status output for a resource
    alloc       Interact with allocations
    job         Interact with jobs
    node        Interact with nodes
    agent       Runs a Nomad agent

Other commands:
    acl             Interact with ACL policies and tokens
    agent-info      Display status information about the local agent
    deployment      Interact with deployments
    eval            Interact with evaluations
    namespace       Interact with namespaces
    operator        Provides cluster-level tools for Nomad operators
    quota           Interact with quotas
    sentinel        Interact with Sentinel policies
    server          Interact with servers
    ui              Open the Nomad Web UI
    version         Prints the Nomad version
```
