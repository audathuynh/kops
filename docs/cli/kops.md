## kops

kops is Kubernetes ops.

### Synopsis


kops is Kubernetes ops. 

kops is the easiest way to get a production grade Kubernetes cluster up and running. We like to think of it as kubectl for clusters. 

kops helps you create, destroy, upgrade and maintain production-grade, highly available, Kubernetes clusters from the command line.  AWS (Amazon Web Services) is currently officially supported, with GCE and VMware vSphere in alpha support.

### Options

```
      --alsologtostderr                  log to standard error as well as files
      --config string                    config file (default is $HOME/.kops.yaml)
      --log_backtrace_at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log_dir string                   If non-empty, write log files in this directory
      --logtostderr                      log to standard error instead of files (default false)
      --name string                      Name of cluster
      --state string                     Location of state storage
      --stderrthreshold severity         logs at or above this threshold go to stderr (default 2)
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO
* [kops completion](kops_completion.md)	 - Output shell completion code for the given shell (bash or zsh).
* [kops create](kops_create.md)	 - Create a resource by command line, filename or stdin.
* [kops delete](kops_delete.md)	 - Delete clusters,instancegroups, or secrets.
* [kops describe](kops_describe.md)	 - Describe a resource.
* [kops edit](kops_edit.md)	 - Edit clusters and other resrouces.
* [kops export](kops_export.md)	 - Export configuration.
* [kops get](kops_get.md)	 - Get one or many resources.
* [kops import](kops_import.md)	 - Import a cluster.
* [kops replace](kops_replace.md)	 - Replace cluster resources.
* [kops rolling-update](kops_rolling-update.md)	 - Rolling update a cluster.
* [kops secrets](kops_secrets.md)	 - Manage secrets & keys.
* [kops toolbox](kops_toolbox.md)	 - Misc infrequently used commands.
* [kops update](kops_update.md)	 - Update a cluster.
* [kops upgrade](kops_upgrade.md)	 - Upgrade a kubernetes cluster.
* [kops validate](kops_validate.md)	 - Validate a kops cluster.
* [kops version](kops_version.md)	 - Print the kops version information.

