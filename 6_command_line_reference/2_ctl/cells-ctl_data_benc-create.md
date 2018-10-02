## cells-ctl data benc-create

Client method for benchmarking node creates.

### Synopsis

Client method for benchmarking node creates.

```
cells-ctl data benc-create [flags]
```

### Options

```
      --batch int        Floods by group of n
      --flood int        Floods of n create nodes
      --flood-soft int   Floods one after one
  -h, --help             help for benc-create
      --output string    result output file (default "1529416547")
      --path string      Path to the data
      --uuid string      UUID of the data
```

### Options inherited from parent commands

```
      --registry string   Registry used to manage services (default "nats")
      --source string     Source where the data resides
```

### SEE ALSO

* [cells-ctl data](cells-ctl-data)	 - Commands for managing indexed data

###### Auto generated by spf13/cobra on 19-Jun-2018