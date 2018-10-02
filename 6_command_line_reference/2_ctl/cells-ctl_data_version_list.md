## cells-ctl data version list

List all versions for a given node

### Synopsis

List all versions for a given node.

Versions are stored inside the default datasource under the "versions" bucket.


```
cells-ctl data version list [flags]
```

### Options

```
  -h, --help          help for list
  -u, --uuid string   Uuid of the node
```

### Options inherited from parent commands

```
      --registry string   Registry used to manage services (default "nats")
      --source string     Source where the data resides
```

### SEE ALSO

* [cells-ctl data version](cells-ctl-data-version)	 - Manage files versioning

###### Auto generated by spf13/cobra on 19-Jun-2018