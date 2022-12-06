## provider-services query ibc channel packet-commitments

Query all packet commitments associated with a channel

### Synopsis

Query all packet commitments associated with a channel

```
provider-services query ibc channel packet-commitments [port-id] [channel-id] [flags]
```

### Examples

```
<appd> query ibc channel packet-commitments [port-id] [channel-id]
```

### Options

```
      --count-total       count total number of records in packet commitments associated with a channel to query for
      --height int        Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help              help for packet-commitments
      --limit uint        pagination limit of packet commitments associated with a channel to query for (default 100)
      --offset uint       pagination offset of packet commitments associated with a channel to query for
  -o, --output string     Output format (text|json) (default "text")
      --page uint         pagination page of packet commitments associated with a channel to query for. This sets offset to a multiple of limit (default 1)
      --page-key string   pagination page-key of packet commitments associated with a channel to query for
      --reverse           results are sorted in descending order
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID
      --node string       The node address (default "http://localhost:26657")
```

### SEE ALSO

* [provider-services query ibc channel](provider-services_query_ibc_channel.md)	 - IBC channel query subcommands

###### Auto generated by spf13/cobra on 5-Dec-2022