## minishift service

Gets the URL for the specified service in your local cluster

### Synopsis


Gets the URL for the specified service in your local cluster

```
minishift service [flags] SERVICE
```

### Options

```
      --format string      Format to output service URL in (default "http://{{.IP}}:{{.Port}}")
      --https              Open the service URL with https instead of http
  -n, --namespace string   The service namespace (default "default")
      --url                Display the kubernetes service URL in the CLI instead of opening it in the default browser
```

### Options inherited from parent commands

```
      --alsologtostderr                  log to standard error as well as files
      --log-flush-frequency duration     Maximum number of seconds between log flushes (default 5s)
      --log_backtrace_at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log_dir string                   If non-empty, write log files in this directory (default "")
      --logtostderr                      log to standard error instead of files
      --show-libmachine-logs             Whether or not to show logs from libmachine.
      --stderrthreshold severity         logs at or above this threshold go to stderr (default 2)
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO
* [minishift](minishift.md)	 - Minishift is a tool for managing local OpenShift clusters.
* [minishift service list](minishift_service_list.md)	 - Lists the URLs for the services in your local cluster

