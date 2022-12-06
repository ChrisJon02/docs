## provider-services query market bid list

Query for all bids

```
provider-services query market bid list [flags]
```

### Options

```
      --count-total       count total number of records in bids to query for
      --dseq uint         deployment sequence to filter
      --gseq uint32       group sequence to filter (default 1)
      --height int        Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help              help for list
      --limit uint        pagination limit of bids to query for (default 100)
      --offset uint       pagination offset of bids to query for
      --oseq uint32       order sequence to filter (default 1)
  -o, --output string     Output format (text|json) (default "text")
      --owner string      bid owner address to filter
      --page uint         pagination page of bids to query for. This sets offset to a multiple of limit (default 1)
      --page-key string   pagination page-key of bids to query for
      --provider string   bid provider address to filter
      --reverse           results are sorted in descending order
      --state string      bid state to filter (open,matched,lost,closed)
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID
      --node string       The node address (default "http://localhost:26657")
```

### SEE ALSO

* [provider-services query market bid](provider-services_query_market_bid.md)	 - Bid query commands

###### Auto generated by spf13/cobra on 5-Dec-2022